# Date Ranges

A dateRange is an Earth Engine parameter object that represents the span of time from the beginning of “start” date onward until (but not including) the beginning of an “end” date.  DateRanges can be processed by using operations of the types listed below, which vary according to the nature of that processing.  Each operation name is linked to a separate page describing that operation.	

#### Creating DateRanges
- [ee.DateRange](ee.DateRange.md)
- [ee.DateRange.unbounded](ee.DateRange.unbounded.md)     

#### Transforming DateRanges
- [dateRange.union](dateRange.union.md)
- [dateRange.intersection](dateRange.intersection.md)

#### Querying DateRanges
- [dateRange.start](dateRange.start.md)
- [dateRange.end](dateRange.end.md)

#### Describing DateRanges
- [dateRange.intersects](dateRange.intersects.md)
- [dateRange.contains](dateRange.contains.md)
- [dateRange.isEmpty](dateRange.isEmpty.md)
- [dateRange.isUnbounded](dateRange.isUnbounded.md)

#### Documenting DateRanges
- [dateRange.getInfo](dateRange.getInfo.md)
- [ee.Algorithms.Describe(dateRange)](ee.Algorithms.Describe.md) 
- [dateRange.toString](dateRange.toString.md)
- [dateRange.serialize](dateRange.serialize.md)

#### Presenting DateRanges
- [print(dateRange)](print.dateRange.md)
- [console.log(dateRange)](console.log.dateRange.md)
- [alert(dateRange)](alert.dateRange.md)
- [confirm(dateRange)](confirm.dateRange.md)
