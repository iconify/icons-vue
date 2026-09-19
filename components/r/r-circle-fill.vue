<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxuo-fmrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sxuo-fmrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:r-circle-fill" /></template>
