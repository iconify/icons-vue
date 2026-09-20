<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3jjpgbqp.css';
import '../../css/r/rvcx90b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d3jjpgbqp"/><path clip-rule="evenodd" class="rvcx90b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:view-page-facing-16" /></template>
