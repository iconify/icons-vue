<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/c/cn7ft0bub.css';
import '../../css/g/gvl5rbbth.css';
import '../../css/v/vu7icbcnb.css';
import '../../css/y/yihsiub0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="cn7ft0bub wm-shadow"/><path class="gvl5rbbth wm-shadow"/><path class="vu7icbcnb"/><path class="yihsiub0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:zoom-out" /></template>
