<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd9y6e3na.css';
import '../../css/p/pvyz65bxh.css';
import '../../css/t/tvasz164u.css';
import '../../css/g/g23x1rbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zd9y6e3na"/><path class="pvyz65bxh"/><path class="tvasz164u"/><path class="g23x1rbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:stats-bars" /></template>
