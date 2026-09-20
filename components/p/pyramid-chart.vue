<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0f47ac3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k0f47ac3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:pyramid-chart" /></template>
