<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_wcabwja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e_wcabwja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:markup-stroke-16" /></template>
