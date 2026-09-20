<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ov-7mhb7f.css';
import '../../css/s/sc1y-lb6c.css';
import '../../css/h/h3tsf1b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ov-7mhb7f"/><path class="sc1y-lb6c"/><path class="h3tsf1b3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smart-home2-filled" /></template>
