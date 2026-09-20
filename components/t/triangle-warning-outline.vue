<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcezmhb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vcezmhb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:triangle-warning-outline" /></template>
