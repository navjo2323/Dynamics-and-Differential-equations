figure(3)
clf
N = 100000;
x = rand(N,1);
y= rand(N,1);
for j = 1:1000
    probab = ceil(rand(N,1)*2);
    p1 = (probab==1);
    p2 = (probab==2);
    x = (x/3).*p1 + (x/3 + 2/3).*p2;
    
end
for j = 1:1000
    probab = ceil(rand(N,1)*2);
    p1 = (probab==1);
    p2 = (probab==2);
    y = (y/3).*p1 + (y/3 + 2/3).*p2;
    
end

plot(x,y,'.')
hold all
