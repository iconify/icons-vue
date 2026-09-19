<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbe60jbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pbe60jbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sort-stroke-16" /></template>
