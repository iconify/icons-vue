<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d4gttkb5z.css';
import '../../css/p/px4c0dbsn.css';
import '../../css/f/fbpyyfbwu.css';
import '../../css/b/bg2yi7zyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="d4gttkb5z"/><path class="px4c0dbsn"/><path class="fbpyyfbwu"/><path class="bg2yi7zyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:sort-numeric-down" /></template>
