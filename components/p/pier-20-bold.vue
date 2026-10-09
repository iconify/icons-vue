<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7txqyfjs.css';
import '../../css/p/px4lcrqbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r7txqyfjs"/><path class="px4lcrqbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pier-20-bold" /></template>
