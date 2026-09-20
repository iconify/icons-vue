<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuy5q6b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cuy5q6b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:recycling" /></template>
