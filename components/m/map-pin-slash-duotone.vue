<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sg5g8obyv.css';
import '../../css/s/sgwj7m_pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="sg5g8obyv"/><path class="sgwj7m_pu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:map-pin-slash-duotone" /></template>
