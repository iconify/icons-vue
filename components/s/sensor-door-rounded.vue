<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmjta5k8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sensor-door-rounded" /></template>
<style>
.qmjta5k8f {
  fill: currentColor;
  d: path("M6.616 21q-.667 0-1.141-.475T5 19.386V4.615q0-.666.475-1.14T6.615 3h10.77q.666 0 1.14.475T19 4.615v14.77q0 .666-.475 1.14t-1.14.475zm8.882-8q.416 0 .709-.291t.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293");
}

</style>
