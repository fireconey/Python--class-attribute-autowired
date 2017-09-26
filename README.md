# Python--class-attribute-autowired
from autowired.autowired import w as ok

op=ok()

p2=ok()

@op.regist

class person:
	name=2
	age=2

@op.auto
class op:
	name=[]
	age=[]

@p2.regist
class ui:
	name=34
	age=67
@p2.auto
class gh:
	name=[]
	age=[]
print(op.name)
print(gh.name) 
