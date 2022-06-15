<template>
  <input type="text" :class="$style.fancyClass" />
</template>

<script>
export default {
  name: "TextBox",
};
</script>

<style lang="scss" module>
.fancyClass {
  color: red;
}
</style>
