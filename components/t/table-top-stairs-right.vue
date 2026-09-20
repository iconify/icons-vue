<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2804ochd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="m2804ochd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-stairs-right" /></template>
