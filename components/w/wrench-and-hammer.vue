<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl6n36bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vl6n36bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wrench-and-hammer" /></template>
