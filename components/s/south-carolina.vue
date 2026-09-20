<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr8d5qbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cr8d5qbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:south-carolina" /></template>
