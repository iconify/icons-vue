<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pegl9qc8z"/><path class="xzmfkyb5o"/><path class="fk0i58bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vidyoconnect" /></template>
<style>
.fk0i58bvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.844 35.907V42.5H9.5a4 4 0 0 1-4-4V25.156h6.593m0-2.312H5.5V9.5a4 4 0 0 1 4-4h13.344v6.593m2.312 0V5.5H38.5a4 4 0 0 1 4 4v13.344h-6.593m0 2.312H42.5V38.5a4 4 0 0 1-4 4H25.156v-6.593M21.5 21.5h5v5h-5z");
}

.pegl9qc8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.093 12.093h23.815v23.815H12.093z");
}

.xzmfkyb5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.063 17.063h13.875v13.875H17.063zm6.937 0v-4.97M30.938 24h4.969M24 30.938v4.969M17.063 24h-4.97");
}

</style>
