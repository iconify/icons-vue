<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iapulzwlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-eye" /></template>
<style>
.iapulzwlm {
  fill: currentColor;
  d: path("M4 14.885h6.18q-.707.627-1.371 1.482q-.665.856-1.35 1.94q.282.47.542.884q.26.413.565.809h-2.95q-.667 0-1.141-.474T4 18.384zm0-1V8.769h7.5v4.96q-.058.035-.112.072t-.107.084zm8.5-5.116H20v4.556q-.87-.438-1.828-.651q-.959-.212-2.037-.212q-1.012 0-1.906.189t-1.729.582zm-8.5-1V5.615q0-.666.475-1.14T5.615 4h12.77q.666 0 1.14.475T20 5.615V7.77zm12.134 14q-1.832 0-3.382-.94t-2.483-2.521q.933-1.581 2.483-2.522t3.383-.94t3.382.94T22 18.309q-.933 1.58-2.483 2.52q-1.55.941-3.383.941m1.257-2.205q.513-.513.513-1.256t-.513-1.256t-1.256-.513t-1.256.512t-.513 1.256t.512 1.257t1.256.513t1.257-.513m-1.963-.547q-.293-.291-.293-.707t.29-.709t.707-.293t.71.29t.293.708t-.291.709t-.707.293t-.709-.291");
}

</style>
