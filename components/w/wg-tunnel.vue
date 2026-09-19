<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ob69nnj8f"/><path class="zqo3fhb0q"/><path class="b6we_qu7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wg-tunnel" /></template>
<style>
.b6we_qu7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.142 21.802a11 11 0 0 1-.376-2.862c0-3.838 1.896-6.95 4.234-6.95s4.234 3.112 4.234 6.95h0c0 .987-.128 1.963-.376 2.862m-3.098 5.441l.892 3.103h-3.304l.892-3.103m2.236-1.281c0 .825-.66 1.494-1.476 1.494s-1.477-.669-1.477-1.494h0c0-.825.661-1.494 1.477-1.494s1.476.669 1.476 1.494");
}

.ob69nnj8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5c-4.384 4.935-10.05 6.386-17.155 3.938C6.845 28.794 10.788 34.174 24 43.5c13.213-9.326 17.155-14.706 17.155-35.062C34.051 10.886 28.384 9.434 24 4.5");
}

.zqo3fhb0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.187 21.796h13.626v11.221H17.187z");
}

</style>
