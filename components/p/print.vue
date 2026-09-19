<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktjmdlb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ktjmdlb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:print" /></template>
