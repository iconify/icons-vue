<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anyoepzyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-landscape-short-outline-sharp" /></template>
<style>
.anyoepzyc {
  fill: currentColor;
  d: path("M5 6.752v10.229zm10.192-2.758Q12.735 5.05 10.21 5.867T5 6.752v10.229q2.714-.137 5.255-1.067t4.937-2.227zM4.77 17.981L4 17.21v-1.095H3v-1.693h1V9.321H3V7.63h1V5.752q3.023-.079 5.893-.92q2.87-.84 5.632-2.06l.667.524v11.016q-2.686 1.448-5.528 2.484q-2.843 1.037-5.895 1.185m0 0v-1H19V6.763h-3.308v-1H20v12.218z");
}

</style>
