<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m67d1bslg.css';
import '../../css/q/qrh9bcbol.css';
import '../../css/r/rym_lvhsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="m67d1bslg"/><path class="qrh9bcbol"/><path class="rym_lvhsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:student" /></template>
