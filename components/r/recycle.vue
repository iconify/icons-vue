<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upz_b1bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="upz_b1bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:recycle" /></template>
