<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q73kw6bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="q73kw6bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:time-sand" /></template>
