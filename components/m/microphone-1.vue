<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/az2rambwo.css';
import '../../css/e/ed3yr9bfb.css';
import '../../css/r/r5gg-lb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="az2rambwo"/><path class="ed3yr9bfb"/><path clip-rule="evenodd" class="r5gg-lb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:microphone-1" /></template>
