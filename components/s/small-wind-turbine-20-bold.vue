<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flvfhbxkj.css';
import '../../css/e/epd7hgbik.css';
import '../../css/i/iw_3o3g9q.css';
import '../../css/d/dq1tynbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="flvfhbxkj"/><path class="epd7hgbik"/><path class="iw_3o3g9q"/><path class="dq1tynbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:small-wind-turbine-20-bold" /></template>
