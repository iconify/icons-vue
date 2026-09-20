<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9ydt-b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x9ydt-b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tennessee-with-capital-star" /></template>
