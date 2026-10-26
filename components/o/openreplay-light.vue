<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/as3pgvova.css';
import '../../css/g/gcjjsc2cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<g class="ft5dv1b6b"><path class="as3pgvova"/><path class="gcjjsc2cx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openreplay-light" /></template>
