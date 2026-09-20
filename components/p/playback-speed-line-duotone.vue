<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/br4_5duwz.css';
import '../../css/n/n5cix9iyo.css';
import '../../css/n/nssu5butl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="br4_5duwz"/><path class="n5cix9iyo"/><path class="nssu5butl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playback-speed-line-duotone" /></template>
