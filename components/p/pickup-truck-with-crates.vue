<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utvx-g6zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="utvx-g6zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-with-crates" /></template>
