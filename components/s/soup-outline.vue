<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqvgzjbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sqvgzjbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:soup-outline" /></template>
