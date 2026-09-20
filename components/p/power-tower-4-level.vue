<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsgjtvbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zsgjtvbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-4-level" /></template>
