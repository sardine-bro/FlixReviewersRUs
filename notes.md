Movie Review App

User
- has_many :reviews


Review
- belongs_to :user

Category
- has many users through reviews

Comment
- belongs_to :user
- belongs_to :review
- text
