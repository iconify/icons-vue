<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apoqu8bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="apoqu8bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:square" /></template>
