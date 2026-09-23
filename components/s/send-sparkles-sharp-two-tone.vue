<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/mrwdvvw0o.css';
import '../../css/u/uecn1lb3p.css';
import '../../css/k/kgawvdakg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mrwdvvw0o"/><path class="uecn1lb3p"/><path class="kgawvdakg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-sparkles-sharp-two-tone" /></template>
