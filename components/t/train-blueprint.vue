<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/g-sgu6b1d.css';
import '../../css/v/vae2kkbgb.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/a/a53k2acqr.css';
import '../../css/g/gt402wbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="g-sgu6b1d wm-deco"/><path class="vae2kkbgb wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="a53k2acqr wm-k"/><path class="gt402wbqt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:train-blueprint" /></template>
