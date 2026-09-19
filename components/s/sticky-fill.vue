<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wig1eedxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wig1eedxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sticky-fill" /></template>
