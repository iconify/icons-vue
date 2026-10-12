<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi-d3bcqw.css';
import '../../css/t/t0gc7texs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yi-d3bcqw"/><path class="t0gc7texs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rabbit-20-bold" /></template>
