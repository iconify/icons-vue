<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gi87txbdj.css';
import '../../css/h/hdcm3gbmg.css';
import '../../css/w/wkd52swho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gi87txbdj"/><path class="hdcm3gbmg"/><path class="wkd52swho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:post-date" /></template>
