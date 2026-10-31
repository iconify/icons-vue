<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/t/tv_dh211h.css';
import '../../css/c/cgh4wkbad.css';
import '../../css/h/hzic4hbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="tv_dh211h wm-shadow"/><path class="cgh4wkbad wm-shadow"/><path class="hzic4hbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:swords" /></template>
