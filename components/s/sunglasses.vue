<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr4x-ojwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xr4x-ojwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sunglasses" /></template>
