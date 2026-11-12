<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mex8whbii.css';
import '../../css/p/px1tg2dxt.css';
import '../../css/a/a2knz85gk.css';
import '../../css/q/q_9c60btz.css';
import '../../css/y/y78fs-s1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mex8whbii"/><path class="px1tg2dxt"/><path class="a2knz85gk"/><path class="q_9c60btz"/><path class="y78fs-s1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:opentofu" /></template>
