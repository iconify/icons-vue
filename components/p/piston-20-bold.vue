<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl4iqhb4q.css';
import '../../css/q/qc3m2d20m.css';
import '../../css/a/azoccq8xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yl4iqhb4q"/><path class="qc3m2d20m"/><path class="azoccq8xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:piston-20-bold" /></template>
