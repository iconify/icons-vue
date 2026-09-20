<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6_cw359x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r6_cw359x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:management-stockout-outline" /></template>
