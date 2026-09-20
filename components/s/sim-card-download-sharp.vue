<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8739hbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sim-card-download-sharp" /></template>
<style>
.r8739hbzm {
  fill: currentColor;
  d: path("m12 16.116l3.308-3.308l-.708-.708l-2.1 2.05V9.5h-1v4.65L9.4 12.1l-.708.708zM5 21V8.423L10.423 3H19v18z");
}

</style>
