<template>
  <div class="footer">
    <footer>
      <p v-html="copyRtSymbol"></p>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      copyRtSymbol: "&copy;Enviro Buddy",
    };
  },
};
</script>

<style scoped>
footer {
  background: #3a6351;
  padding: 5px;
  border-width: 2px;
  text-align: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  height: 5%;
  vertical-align: middle;
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
}
p {
  align-content: center;
  color: #f2edd7;
}
</style>