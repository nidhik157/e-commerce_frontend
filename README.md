# e-commerce_frontend
frontend for e-commerce website

#New changes in Login.js
{action === "Sign Up" 
                        ? 
                        <div className='form-group was-validated mb-2'>
                        <label htmlFor="select-category">Select User Category</label>
                        <select 
                            className="mb-3 d-flex align-items-center justify-content-center" 
                            name="user-category" 
                            id="user-category"
                            required
                        >
                            <option value="Customer">Customer</option>
                            <option value="Seller">Seller</option>
                        </select>
                        <div className="invalid-feedback">
                            Please Select Category
                        </div>
                        </div> 
                        : 
                        <div className='form-group was-validated mb-2'>
                        <label htmlFor="select-category">Select User Category</label>
                        <select 
                            className="mb-3 d-flex align-items-center justify-content-center" 
                            name="user-category" 
                            id="user-category"
                            required
                        >
                            <option value="Customer">Customer</option>
                            <option value="Admin">Admin</option>
                            <option value="Seller">Seller</option>
                        </select>
                        <div className="invalid-feedback">
                            Please Select Category
                        </div>
                    </div>
                    }
