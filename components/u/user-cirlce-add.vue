<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/u4vh7gcjc.css';
import '../../css/d/dnl8j0wnh.css';
import '../../css/u/u6t3q4b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4vh7gcjc"/><path class="dnl8j0wnh"/><path class="u6t3q4b3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-cirlce-add" /></template>
