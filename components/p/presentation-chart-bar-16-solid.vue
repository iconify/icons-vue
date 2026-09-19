<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shjnevbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="shjnevbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:presentation-chart-bar-16-solid" /></template>
