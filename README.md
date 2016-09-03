# Calculator
Multi-digit calculator code:

    var num1 = 0
    var num2 = 0
    var operationUsed = false
    var operationAvailable = false
    var num2Available = false
    var onlyEqual = false
    var operation = 0
    var square = 0.0
    var a = 0
    var b = 0
    var multiple = false
    var addition = false
    var additionSign = "+"
    var subtractSign = "-"
    
    @IBOutlet var number: UILabel!
    
   
    @IBAction func Uno(sender: AnyObject) {
        
        if(operationUsed == false && multiple == false){
            num1 = 1
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                a = a * 10 + num1
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 1
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                    
                }else{
                    if(operationUsed == true && multiple == true){
                        num2 = 1
                        b = b * 10 + num2
                        number.text = "\(b)"
                        onlyEqual = true
                        
                    }
                    
                }
                
            }
            
        }
        
    }
    
    
    
    
    @IBAction func Dos(sender: AnyObject) {
        if(operationUsed == false && multiple == false){
            num1 = 2
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                num1 = 2
                a = a * 10 + num1
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 2
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                    
                }else{
                    if(operationUsed == true && multiple == true){
                        num2 = 2
                        b = b * 10 + num2
                        number.text = "\(b)"
                        onlyEqual = true
                        
                    }
                    
                }
                
            }
            
        }
            }
    @IBAction func Tres(sender: AnyObject) {
        if(operationUsed == false && multiple == false){
            num1 = 3
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                num1 = 3
                a = a * 10 + num1
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 3
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                    
                }else{
                    if(operationUsed == true && multiple == true){
                        num2 = 3
                        b = b * 10 + num2
                        number.text = "\(b)"
                        onlyEqual = true
                        
                    }
                    
                }
                
            }
            
        }
           }

    @IBAction func Cuatro(sender: AnyObject) {
        if(operationUsed == false && multiple == false){
            num1 = 4
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                num1 = 4
                a = a * 10 + num1
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 4
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                }else{
                    if(operationUsed == true && multiple == true){
                        num2 = 4
                        b = b * 10 + num2
                        number.text = "\(b)"
                        onlyEqual = true
                        
                    }
                    
                }
                
            }
            
        }
        
    }
    
    @IBAction func Cinco(sender: AnyObject) {
        if(operationUsed == false && multiple == false){
            num1 = 5
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                num1 = 5
                a = a * 10 + num1
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 5
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                    
                }else{
                    if(operationUsed == true && multiple == true){
                        num2 = 5
                        b = b * 10 + num2
                        number.text = "\(b)"
                        onlyEqual = true
                        
                    }
                    
                }
                
            }
            
        }
            }
    
    @IBAction func Sies(sender: AnyObject) {
        if(operationUsed == false && multiple == false){
            num1 = 6
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                num1 = 6
                a = a * 10 + num1
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 6
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                }else{
                    if(operationUsed == true && multiple == true){
                        num2 = 6
                        b = b * 10 + num2
                        number.text = "\(b)"
                        onlyEqual = true
                        
                    }
                    
                }
                
            }
            
        }
        
    }
    @IBAction func Siete(sender: AnyObject) {
        if(operationUsed == false && multiple == false){
            num1 = 7
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                num1 = 7
                a = a * 10 + num1
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 7
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                    
                }else{
                    if(operationUsed == true && multiple == true){
                        num2 = 7
                        b = b * 10 + num2
                        number.text = "\(b)"
                        onlyEqual = true
                        
                    }
                    
                }
                
            }
            
        }
        
    }
    @IBAction func Ocho(sender: AnyObject) {
        if(operationUsed == false && multiple == false){
            num1 = 8
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                num1 = 8
                a = a * 10 + num1
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 8
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                    
                }else{
                    if(operationUsed == true && multiple == true){
                        num2 = 8
                        b = b * 10 + num2
                        number.text = "\(b)"
                        
                    }
                    
                }
                
            }
            
        }
        
    }
    
    @IBAction func Nueve(sender: AnyObject) {
        if(operationUsed == false && multiple == false){
            num1 = 9
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                num1 = 9
                a = a * 10 + num1
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 9
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                    
                }else{
                    if(operationUsed == true && multiple == true){
        

                        num2 = 9
                        b = b * 10 + num2
                        number.text = "\(b)"
                        
                    }
                    
                }
                
            }
            
        }
        
    }
    @IBAction func Zero(sender: AnyObject) {
        if(operationUsed == false && multiple == false){
            num1 = 0
            a = num1
            number.text = "\(a)"
            multiple = true
            operationAvailable = true
        }else{
            if(operationUsed == false && multiple == true){
                num1 = 0
                a = a * 10
                number.text = "\(a)"
                operationAvailable = true
                
            }else{
                if(operationUsed == true && multiple == false){
                    num2 = 0
                    b = num2
                    number.text = "\(b)"
                    multiple = true
                    onlyEqual = true
                    
                    
                }else{
                    if(operationUsed == true && multiple == true){
                        num2 = 0
                        b = b * 10
                        number.text = "\(b)"
                        
                    }
                    
                }
                
            }
            
        }
        
    }



    @IBAction func addition(sender: AnyObject) {
        if(operationAvailable == true){
            number.text = "+"
            operationUsed = true
            num2Available = true
            operation = 1
            multiple = false
        }
    }
    
    
    @IBAction func minus(sender: AnyObject) {
        if(operationAvailable == true){
            number.text = "-"
            operationUsed = true
            num2Available = true
            operation = 2
            multiple = false
        }
    }

    
    @IBAction func Times(sender: AnyObject) {
        if(operationAvailable == true){
            number.text = "*"
            operationUsed = true
            num2Available = true
            operation = 3
            multiple = false
           
        }
    }
    
    @IBAction func Divide(sender: AnyObject) {
        if(operationAvailable == true){
            number.text = "÷"
            operationUsed = true
            num2Available = true
            operation = 4
            multiple = false
            
        }
    }
    

    
    @IBAction func equal(sender: AnyObject) {
        if(onlyEqual == true){
            if(operation == 1){
                number.text = "\(a + b)"
            }
            if(operation == 2){
                number.text = "\(a - b)"
            }
            if(operation == 3){
                number.text = "\(a * b)"
            }
            if(operation == 4){
                number.text = "\(a / b)"
            }
            
        }else{
            if(onlyEqual == true && addition == true){
                number.text = "\(a + b)"
            }
            
        }
    }
    

    
    @IBAction func Reset(sender: AnyObject) {
        num1 = 0
        num2 = 0
        operationUsed = false
        operationAvailable = false
        num2Available = false
        onlyEqual = false
        a = 0
        b = 0
        multiple = false
        
        number.text = "###"
    }
    


