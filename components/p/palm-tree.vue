<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/ew9tz4bmz.css';
import '../../css/w/w1fsq0zwn.css';
import '../../css/f/f5bz_s3tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ew9tz4bmz wm-shadow"/><path class="w1fsq0zwn wm-shadow"/><path class="f5bz_s3tr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:palm-tree" /></template>
