<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jld31zsug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jld31zsug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-remove-stroke-16" /></template>
