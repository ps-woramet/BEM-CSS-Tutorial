BEM

B = Block จะตั้งชื่อ (Block)
E = Element ส่วนต่างๆใน Block จะตั้งชื่อ (Block__Element) ใช้เมื่อเป็นส่วนย่อยสุด
M = Modiflyer สิ่งที่ต้องการดัดแปลงใน Element จะตั้งชื่อ (Element--Modiflyer)

<!-- Block -->
div class="card">
    <!-- Element -->
    <div class="card__img">
        <img src="" alt="">
    </div>
    <!-- Element -->
    <div class="card__desc">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos iure a reiciendis odit laudantium accusantium necessitatibus voluptate ab. Omnis quaerat ab repellendus! Quis quibusdam id repellendus error ad eos hic.</p>
    </div>
    <!-- Element -->
    <div class="card__btn-group">
        <!-- Modifier -->
        <button class="card__btn btn--success">View</button>
        <button class="card__btn btn--danger">Delete</button>
    </div>
</div>