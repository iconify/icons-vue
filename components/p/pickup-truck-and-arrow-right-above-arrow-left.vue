<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji2s539xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ji2s539xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-and-arrow-right-above-arrow-left" /></template>
