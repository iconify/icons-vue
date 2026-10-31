<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/d/d2lqw11bx.css';
import '../../css/f/fdhb8fb-x.css';
import '../../css/h/hsgg6j0lp.css';
import '../../css/m/m3mfq9x2i.css';
import '../../css/j/jgwm0beal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="d2lqw11bx"/><path class="fdhb8fb-x wm-s"/><path class="hsgg6j0lp wm-k"/><path class="m3mfq9x2i wm-a"/><path class="jgwm0beal wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:sparkler" /></template>
