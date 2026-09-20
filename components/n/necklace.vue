<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uba5k61oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="uba5k61oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:necklace" /></template>
