<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cw83oib4z.css';
import '../../css/t/t7upphb2s.css';
import '../../css/i/iku2ktmva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="cw83oib4z"/><path class="t7upphb2s"/><path class="iku2ktmva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-golfing" /></template>
