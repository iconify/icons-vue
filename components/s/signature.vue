<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/t/t6y-3unio.css';
import '../../css/d/dj5pntbty.css';
import '../../css/d/diuz99pei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="t6y-3unio wm-shadow"/><path class="dj5pntbty wm-shadow"/><path class="diuz99pei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:signature" /></template>
