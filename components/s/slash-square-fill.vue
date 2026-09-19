<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukh96f2tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ukh96f2tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:slash-square-fill" /></template>
