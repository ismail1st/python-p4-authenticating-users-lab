# TODO - Authentication Implementation

## Step 1: Add Login Resource (/login)

- [ ] Create Login class with post() method
- [ ] Get username from request JSON
- [ ] Query user by username
- [ ] Set session['user_id']
- [ ] Return user as JSON with 200 status

## Step 2: Add Logout Resource (/logout)

- [ ] Create Logout class with delete() method
- [ ] Remove user_id from session
- [ ] Return empty response with 204 status

## Step 3: Add CheckSession Resource (/check_session)

- [ ] Create CheckSession class with get() method
- [ ] Check session for user_id
- [ ] Return user as JSON with 200 or empty with 401

## Step 4: Register Resources with API

- [ ] Add api.add_resource for Login, Logout, CheckSession

## Step 5: Run Tests

- [ ] Execute `pytest -x` to verify implementation
