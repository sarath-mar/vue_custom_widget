<template>
  <div>
    <header class="widget__header">
      <p>Rybbon Form Created</p>
    </header>
    <form>
      <div class="form__field">
        <label for="name">Enter your Name</label>
        <input
          type="text"
          id="name"
          name="name"
          placeholder="Enter your name"
        />
      </div>
      <div class="form__field">
        <label for="email">Email</label>
        <input
          type="email"
          id="email"
          name="email"
          placeholder="Enter your email"
        />
      </div>
      <div class="form__field">
        <label for="subject">Subject</label>
        <input
          type="text"
          id="subject"
          name="subject"
          placeholder="Enter Message Subject"
        />
      </div>
      <div class="form__field">
        <label for="message">Message</label>
        <textarea
          id="message"
          name="message"
          placeholder="Enter your message"
          rows="6"
        ></textarea>
      </div>
      <button>Send Message</button>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
</style>