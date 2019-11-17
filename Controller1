import javafx.event.ActionEvent;
import javafx.fxml.FXML;
import javafx.scene.canvas.Canvas;
import javafx.scene.canvas.GraphicsContext;
import javafx.scene.control.Button;
import javafx.scene.control.TextField;
import javafx.scene.layout.AnchorPane;
import javafx.scene.paint.Color;


public class Controller1 {

    @FXML
    private AnchorPane anchor;
    @FXML
    private Button btn;
    @FXML
    private TextField fieldstartx;
    @FXML
    private TextField fieldstarty;
    @FXML
    private TextField fieldendx;
    @FXML
    private TextField fieldendy;


    @FXML
    private AnchorPane anchor1;
    @FXML
    private Button btn1;
    @FXML
    private TextField fieldstartx1;
    @FXML
    private TextField fieldstarty1;
    @FXML
    private TextField fieldendx1;
    @FXML
    private TextField fieldendy1;


    @FXML
    private AnchorPane anchor2;
    @FXML
    private Button btn2;
    @FXML
    private TextField fieldstartx2;
    @FXML
    private TextField fieldstarty2;
    @FXML
    private TextField fieldendx2;
    @FXML
    private TextField fieldendy2;

    @FXML
    private AnchorPane anchor3;
    @FXML
    private Button btn3;
    @FXML
    private TextField field1;
    @FXML
    private TextField field2;
    @FXML
    private TextField field3;
    @FXML
    private TextField field4;
    @FXML
    private TextField field5;
    @FXML
    private TextField field6;

    public void onClickLine(ActionEvent actionEvent) {
        Canvas canvas = new Canvas();
        canvas.setHeight(350);
        canvas.setWidth(400);
        anchor.getChildren().add(canvas);
        GraphicsContext gr = canvas.getGraphicsContext2D();
        double x=Double.parseDouble(fieldstartx.getText());
        double y=Double.parseDouble(fieldstarty.getText());
        double x1=Double.parseDouble(fieldendx.getText());
        double y1=Double.parseDouble(fieldendy.getText());
        gr.setStroke(Color.BLUE);
        gr.strokeLine(x,y,x1,y1);
    }

    public void onClickRect(ActionEvent actionEvent) {
        Canvas canvas = new Canvas();
        canvas.setHeight(350);
        canvas.setWidth(400);
        anchor1.getChildren().add(canvas);
        GraphicsContext gr = canvas.getGraphicsContext2D();
        double x=Double.parseDouble(fieldstartx1.getText());
        double y=Double.parseDouble(fieldstarty1.getText());
        double x1=Double.parseDouble(fieldendx1.getText());
        double y1=Double.parseDouble(fieldendy1.getText());
        gr.setFill(Color.RED);
        gr.fillRect(x,y,x1,y1);
    }

    public void onClickEllips(ActionEvent actionEvent) {
        Canvas canvas = new Canvas();
        canvas.setHeight(350);
        canvas.setWidth(400);
        anchor2.getChildren().add(canvas);
        GraphicsContext gr = canvas.getGraphicsContext2D();
        double x=Double.parseDouble(fieldstartx2.getText());
        double y=Double.parseDouble(fieldstarty2.getText());
        double x1=Double.parseDouble(fieldendx2.getText());
        double y1=Double.parseDouble(fieldendy2.getText());
        gr.setFill(Color.YELLOW);
        gr.fillOval(x,y,x1,y1);
    }

    public void onClickPolygon(ActionEvent actionEvent) {
        Canvas canvas = new Canvas();
        canvas.setHeight(350);
        canvas.setWidth(400);
        anchor3.getChildren().add(canvas);
        GraphicsContext gr = canvas.getGraphicsContext2D();
        double f1=Double.parseDouble(field1.getText());
        double f2=Double.parseDouble(field2.getText());
        double f3=Double.parseDouble(field3.getText());
        double f4=Double.parseDouble(field4.getText());
        double f5=Double.parseDouble(field5.getText());
        double f6=Double.parseDouble(field6.getText());
        gr.setFill(Color.GREEN);
        gr.fillPolygon(new double[]{f1,f2,f3},new double[]{f4,f5,f6},3);
    }
}
