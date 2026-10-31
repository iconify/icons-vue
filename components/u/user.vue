<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/bwxb4zbru.css';
import '../../css/w/wfy5mof3d.css';
import '../../css/r/rh6thpbkx.css';
import '../../css/d/dnn8z0qmr.css';
import '../../css/x/xltuw1ech.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="bwxb4zbru wm-shadow"/><path class="wfy5mof3d wm-shadow"/><path class="rh6thpbkx"/><path class="dnn8z0qmr"/><path class="xltuw1ech"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:user" /></template>
