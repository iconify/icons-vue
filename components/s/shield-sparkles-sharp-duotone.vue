<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/i43jttb1d.css';
import '../../css/k/ksu4hvb6k.css';
import '../../css/o/ovikvmgdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i43jttb1d"/><path class="ksu4hvb6k"/><path class="ovikvmgdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-sparkles-sharp-duotone" /></template>
