<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmc-gjbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:touch-double-2-outline" /></template>
<style>
.jmc-gjbvu {
  fill: currentColor;
  d: path("M10.412 21q-.547 0-1.04-.215q-.495-.214-.824-.668l-4.917-6.283l.323-.322q.31-.31.755-.356q.445-.047.841.182l2.508 1.54V8.193q0-.194.143-.347q.144-.153.357-.153q.194 0 .347.153t.153.347v8.48l-3.7-2.231l3.97 5.055q.184.258.478.381t.606.123h5.242q.979 0 1.662-.675q.684-.674.684-1.671v-3.788q0-.589-.398-.987t-.986-.398h-2.02v-1h2.02q.98 0 1.682.702T19 13.866v3.788q0 1.401-.983 2.374q-.983.972-2.363.972zm.915-8.52V6.52q0-.195.144-.348t.356-.153q.194 0 .347.153t.153.347v5.962zM4.344 9.159q-.055-.237-.065-.473q-.01-.237-.01-.493q0-2.565 1.797-4.379Q7.864 2 10.46 2q2.575 0 4.375 1.814t1.8 4.378q0 .218-.038.551l-.038.334l-.98-.11l.028-.287q.028-.288.028-.488q0-2.154-1.515-3.673T10.46 3Q8.285 3 6.777 4.517T5.269 8.185v.407q0 .2.05.4zM11.68 16");
}

</style>
