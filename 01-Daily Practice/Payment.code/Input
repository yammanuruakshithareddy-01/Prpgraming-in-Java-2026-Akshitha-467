interface Payment {
    void pay(double amount);
}

class UPI implements Payment {
    @Override
    public void pay(double amount) {
        System.out.println("Payment of ₹" + amount + " made using UPI.");
    }
}

class Card implements Payment {
    @Override
    public void pay(double amount) {
        System.out.println("Payment of ₹" + amount + " made using Card.");
    }
}

class NetBanking implements Payment {
    @Override
    public void pay(double amount) {
        System.out.println("Payment of ₹" + amount + " made using Net Banking.");
    }
}

public class Main {
    public static void main(String[] args) {

        double amount = 1500.00;

        // Interface reference demonstrating runtime polymorphism
        Payment payment;

        payment = new UPI();
        payment.pay(amount);

        payment = new Card();
        payment.pay(amount);

        payment = new NetBanking();
        payment.pay(amount);
    }
}
