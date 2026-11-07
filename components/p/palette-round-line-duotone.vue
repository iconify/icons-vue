<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/w4-05cc6z.css';
import '../../css/s/s-ypsc2gv.css';
import '../../css/j/jgc6khllm.css';
import '../../css/m/mhih08bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w4-05cc6z"/><path class="s-ypsc2gv"/><path class="jgc6khllm"/><path class="mhih08bzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-round-line-duotone" /></template>
