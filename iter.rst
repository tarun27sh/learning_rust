fn main() {
    println!("HW !");
    let  vec = vec![0,1,2,3];
    vec.iter().for_each(|v| println!("{}", v));
    // or
    for v in &vec {
        println!("{}", v);
    }
}
