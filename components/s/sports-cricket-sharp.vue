<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvzdxsttn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-cricket-sharp" /></template>
<style>
.pvzdxsttn {
  fill: currentColor;
  d: path("M11.5 16.854L2.433 7.825l3.392-3.392l9.01 9.086zm7.1 4.454l-4.327-4.327l.708-.708l4.327 4.327zM16.544 7.456q-.813-.814-.813-1.956t.813-1.956t1.956-.813t1.956.813t.813 1.956t-.813 1.956t-1.956.813t-1.956-.813");
}

</style>
