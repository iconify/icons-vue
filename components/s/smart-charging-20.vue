<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhx89lryx.css';
import '../../css/r/r07ubeb7t.css';
import '../../css/d/d6b0ntifu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dhx89lryx"/><path class="r07ubeb7t"/><path class="d6b0ntifu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-charging-20" /></template>
