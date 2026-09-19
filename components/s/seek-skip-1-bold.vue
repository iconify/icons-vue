<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/g/g3xgywz_t.css';
import '../../css/k/k433me6_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="to-5kdesz"><path class="g3xgywz_t"/><path class="k433me6_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seek-skip-1-bold" /></template>
