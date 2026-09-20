<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhgt1i-cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uhgt1i-cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:square-stroked-15" /></template>
