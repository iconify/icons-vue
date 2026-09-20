<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3l75_b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d3l75_b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:order-integral-filled" /></template>
