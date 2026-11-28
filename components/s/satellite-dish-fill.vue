<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkza26tve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vkza26tve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:satellite-dish-fill" /></template>
