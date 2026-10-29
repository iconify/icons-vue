<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ob5i9b1dp.css';
import '../../css/x/xz0z_ni8b.css';
import '../../css/c/c2tvjprfg.css';
import '../../css/f/fvbk-8bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ob5i9b1dp"/><path class="xz0z_ni8b"/><path class="c2tvjprfg wm-a"/><path class="fvbk-8bio wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paper-fan" /></template>
