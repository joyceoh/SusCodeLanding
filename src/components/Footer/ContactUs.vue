<script lang="ts">
export default {
    name: 'ContactUs',
}
</script>

<template>
  <section id="contactus">
        <div>
            <span class="contactus-heading">CONTACT US</span>
        </div>

        <div class="contact">
        <div>
          <a class="contact-span" href= "mailto: suscodeapp@gmail.com">Email Us</a>
          <a class="contact-span" href="https://x.com/suscode_"><span>Follow us on X!</span></a>
          <a class="contact-span" href="https://www.linkedin.com/company/suscode/"><span>Stay up to date with us on LinkedIn</span></a>
        </div>
        </div>
    </section>
</template>

<style lang="css">
#contactus {
    background: linear-gradient(to bottom, #242424 25%, #000000 100%);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      width: 100vw;
      height: 75vh;
      scroll-margin-top: 125px;
  }

  .contactus-heading {
  display: inline;
  font-size: 5rem;
  font-weight: bold;
  background: linear-gradient(142deg, rgba(122,164,212,1) 0%, rgba(4,48,111,1) 35%, rgba(4,94,222,1) 100%);
  background-clip: text;
  color: transparent;
  margin-top: -2rem;
}

  .contactus-span {
    height: 80vh;
    width: 60vw;
    background: linear-gradient(142deg, rgb(0, 44, 94) 0%, rgba(4,48,111,1) 35%, rgba(4,94,222,1) 100%);
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding: 2em;
    box-shadow: 0px 5px 20px rgb(0, 44, 94), 0px 5px 20px #fff;
    transition: all ease 0.5s;
    color: #fff;
  }

  .contactus-span:hover {
  transform: translateY(-10px);
  box-shadow: 0px 15px 30px #fff;
  }

  .contactus-span span {
    font-size: 1rem;
    font-weight: 600;
    text-align: center;
  }

  .contact {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  width: 100vw;
  padding: 2rem;
  box-sizing: border-box;
}

.contact div {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  width: 100%;
  gap: 1.5rem;
}

.contact-span {
  background: linear-gradient(142deg, rgb(0, 44, 94) 0%, rgba(4,48,111,1) 35%, rgba(4,94,222,1) 100%);
  border-radius: 10px;
  width: 25%;
  min-width: 250px;
  padding: 2em;
  box-shadow: 0px 5px 20px rgb(0, 44, 94), 0px 5px 20px #fff;
  transition: all ease 0.5s;
  color: #fff;
  margin: 1rem;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.contact-span:hover {
  transform: translateY(-10px);
  box-shadow: 0px 15px 30px #fff;
}

.contact-span span {
  font-size: 1rem;
  font-weight: 600;
}

.text {
    color: rgb(189, 189, 189);
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>