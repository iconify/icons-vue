<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug54_cbfy.css';
import '../../css/w/wfiymubcg.css';
import '../../css/q/q5gb5d1vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ug54_cbfy"/><path class="wfiymubcg"/><path class="q5gb5d1vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rugby-20-bold" /></template>
