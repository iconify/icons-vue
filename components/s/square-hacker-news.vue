<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvbm_mbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="pvbm_mbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-hacker-news" /></template>
