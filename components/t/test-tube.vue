<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/y/ypx0kvb5q.css';
import '../../css/f/fxpg8qb2i.css';
import '../../css/a/a2jwf8b5s.css';
import '../../css/i/ianen82vg.css';
import '../../css/l/lfucqd9kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow ypx0kvb5q"/><path class="fxpg8qb2i wm-shadow"/><path class="a2jwf8b5s"/><path class="ianen82vg"/><path class="lfucqd9kg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:test-tube" /></template>
