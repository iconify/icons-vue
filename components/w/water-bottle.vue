<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulv4xq14x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ulv4xq14x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-bottle" /></template>
