<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sz4revdyj.css';
import '../../css/m/mo0h-x4lp.css';
import '../../css/r/ru0g9b5-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sz4revdyj"/><path class="mo0h-x4lp"/><path class="ru0g9b5-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:nut" /></template>
