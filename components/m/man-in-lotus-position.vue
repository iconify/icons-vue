<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4u8pbwjc.css';
import '../../css/s/sgctswr3q.css';
import '../../css/m/map-b7bpq.css';
import '../../css/o/os1uj79jw.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/z/ztg5wmoma.css';
import '../../css/h/hiot3ubwz.css';
import '../../css/r/rnbfaib6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="x4u8pbwjc"><circle class="sgctswr3q"/><path class="map-b7bpq"/><path class="os1uj79jw"/></g><g class="brzn_0bpr"><circle class="ztg5wmoma"/><path class="hiot3ubwz"/><path class="rnbfaib6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:man-in-lotus-position" /></template>
