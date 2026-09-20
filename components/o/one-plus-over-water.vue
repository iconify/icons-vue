<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg_i751ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xg_i751ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:one-plus-over-water" /></template>
