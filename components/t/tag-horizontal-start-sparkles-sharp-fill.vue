<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zye0l-oxa.css';
import '../../css/d/dosjo21sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zye0l-oxa"/><path class="dosjo21sx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-start-sparkles-sharp-fill" /></template>
