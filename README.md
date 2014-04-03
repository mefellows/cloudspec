CloudSpec
=========

CloudSpec is a Testing Framework for your cloud environment.

Example
=======
describe server('foo') do
  it {
    // not be able to be communicated with over port 80"
    should !portOpen(80)
  }
end   
