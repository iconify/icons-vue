<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h7e2b6-4b.css';
import '../../css/t/t267_cb-w.css';
import '../../css/j/jmk2flbmo.css';
import '../../css/y/yh64wcc-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="h7e2b6-4b"/><path class="t267_cb-w"/><path class="jmk2flbmo"/><path class="yh64wcc-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:tachometer-7" /></template>
