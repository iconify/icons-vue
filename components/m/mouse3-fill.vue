<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrog20bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lrog20bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:mouse3-fill" /></template>
