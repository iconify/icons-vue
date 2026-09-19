<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/la_v_lbyo.css';
import '../../css/t/tj3-sfldn.css';
import '../../css/r/rhxe-ug5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="la_v_lbyo"/><path class="tj3-sfldn"/><path class="rhxe-ug5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:touch-10" /></template>
