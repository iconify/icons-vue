<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awr86_bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="awr86_bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:park-outline" /></template>
