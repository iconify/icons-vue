<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ooks_4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:watch-button-outline-rounded" /></template>
<style>
.v_ooks_4x {
  fill: currentColor;
  d: path("M6.183 19.006q-.164.586-.359 1.154q-.195.567-.499 1.148q-.073.183-.278.24q-.205.058-.381-.046t-.244-.296q-.066-.192.032-.375q1.067-2.14 1.22-4.306T5.827 12q0-2.315-.153-4.484T4.46 3.225q-.098-.188-.038-.393t.244-.309t.377-.033q.196.07.288.252q.285.562.486 1.12q.202.557.366 1.138H8.23q1.4.006 2.373 1.024t.973 2.482v7.019q0 1.458-.973 2.47q-.973 1.01-2.373 1.01zM16.402 12.5l1.63 1.727q.141.16.141.351t-.165.357q-.16.16-.364.15t-.344-.17l-2.273-2.35q-.223-.242-.223-.565t.223-.565l2.273-2.35q.146-.166.344-.163t.364.169q.14.146.153.344t-.134.363L16.402 11.5H20.5q.214 0 .357.143T21 12t-.143.357t-.357.143zm-9.977 5.506h1.806q.979 0 1.662-.735q.684-.734.684-1.771V8.48q0-1.016-.684-1.748T8.231 6H6.419q.287 1.437.347 2.91q.061 1.475.061 3.09q0 1.621-.058 3.105q-.057 1.483-.344 2.9M6.827 12");
}

</style>
