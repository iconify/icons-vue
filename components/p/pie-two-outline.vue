<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-zpnqbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f-zpnqbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:pie-two-outline" /></template>
