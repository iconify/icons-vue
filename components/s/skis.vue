<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fvm-rjbdm.css';
import '../../css/f/fgi84lb4i.css';
import '../../css/k/kxzi-1bcp.css';
import '../../css/m/mhb6sub6m.css';
import '../../css/v/vkst6lb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fvm-rjbdm"/><path class="fgi84lb4i"/><path class="kxzi-1bcp"/><path class="mhb6sub6m"/><path class="vkst6lb4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:skis" /></template>
