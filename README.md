# aidy
paidy payload array

# use node-rest-client to get json
# 
{ id: 'pay_WvLwQE4AAFQA1234',
  created_at: '2018-05-09T12:57:36.342Z',
  expires_at: '2018-06-08T12:57:38.075Z',
  amount: 100,
  currency: 'JPY',
  description: 'Sample store',
  store_name: '(Paidy sample store)',
  test: true,
  status: 'authorized',
  tier: 'classic',
  buyer: 
   { name1: '$B$9$:$-!!<!O:(B',
     name2: null,
     email: 'successful.payment@paidy.com',
     phone: '818000000001' },
  order: 
   { tax: 0,
     shipping: 0,
     order_ref: '20161214ato06',
     items: [ [Object] ],
     updated_at: null },
  shipping_address: 
   { line1: 'AXIS$B%S%k(B 10F',
     line2: '$BO;K\LZ(B4-22-1',
     city: '$B9A6h(B',
     state: '$BEl5~ET(B',
     zip: '106-2004' },
  captures: [],
  refunds: [],
  metadata: {} }

# data.order.items

[ { id: 'PDI001',
    title: 'Paidy$B%9%K!<%+!<(B',
    description: ' ',
    unit_price: 100,
    quantity: 1 } ]
