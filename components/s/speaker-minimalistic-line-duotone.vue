<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sng0m5e4g.css';
import '../../css/r/ryndaxq8c.css';
import '../../css/i/irudeebhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sng0m5e4g"/><path class="ryndaxq8c"/><path class="irudeebhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speaker-minimalistic-line-duotone" /></template>
