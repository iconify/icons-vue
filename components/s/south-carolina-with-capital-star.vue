<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_h4-1b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t_h4-1b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:south-carolina-with-capital-star" /></template>
