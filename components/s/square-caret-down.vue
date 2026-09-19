<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3j1eqb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="d3j1eqb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:square-caret-down" /></template>
