<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v4k7c2urc"/><path class="tre5rhnqy"/><path class="llb-z3b9z"/><path class="eisyv-03s"/><path class="s4gmg9beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swisstransfer" /></template>
<style>
.eisyv-03s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.963 38.43V22.263c0-.777-.658-1.175-1.401-1.403l-16.207-4.968");
}

.llb-z3b9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.688 13.2L16.626 8.584a.8.8 0 0 0-.275-.038c-.624.022-1.128.761-1.128 1.44v2.628l16.207 4.968c.742.227 1.4.626 1.4 1.402v16.17l2.46.753c.742.228 1.4-.626 1.4-1.403V17.717");
}

.s4gmg9beb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.964 32.375l2.376-5.844l1.972 2.566l3.847-6.724l3.802 13.66l-3.563-1.128l-.24-3.676l-1.929 3.082z");
}

.tre5rhnqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.483 11.824c-.624.021-1.128.76-1.128 1.44v2.627l16.207 4.969c.743.227 1.4.626 1.4 1.402v16.169l2.46.754c.742.227 1.4-.626 1.4-1.403V18.984c0-.776-.658-1.175-1.4-1.402l-18.664-5.72a.8.8 0 0 0-.275-.038");
}

.v4k7c2urc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.951 5.5v13.107m.001-2.784l5.933-5.904m-4.045 4.025l4.664 4.643m-29.149-2.696L8.9 15.138c-.743-.228-1.403.626-1.403 1.402v18.798c0 .777.66 1.175 1.403 1.403l18.663 5.722c.743.227 1.4-.626 1.4-1.403v-2.63");
}

</style>
