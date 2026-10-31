<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/t/tzn2_abpy.css';
import '../../css/d/dggy76bvx.css';
import '../../css/s/sf3y2ibxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="tzn2_abpy wm-shadow"/><path class="dggy76bvx wm-shadow"/><path class="sf3y2ibxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:qr-code" /></template>
