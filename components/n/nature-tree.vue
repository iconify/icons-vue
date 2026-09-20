<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwb25ab6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uwb25ab6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:nature-tree" /></template>
