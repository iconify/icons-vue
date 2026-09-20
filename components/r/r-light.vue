<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn6yq3b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rn6yq3b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:r-light" /></template>
