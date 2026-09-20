<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_6nrkjdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tornado-sharp" /></template>
<style>
.n_6nrkjdq {
  fill: currentColor;
  d: path("M2.73 4h18.54l-2.612 4.5H5.342zm3.186 5.5h12.169l-2.327 4H8.242zm2.9 5h6.368L12 20z");
}

</style>
