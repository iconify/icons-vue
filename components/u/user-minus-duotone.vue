<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/om8z0cb6g.css';
import '../../css/g/g7-z5_thi.css';
import '../../css/r/ry6kafxvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="om8z0cb6g"/><path class="g7-z5_thi"/><path class="ry6kafxvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-minus-duotone" /></template>
