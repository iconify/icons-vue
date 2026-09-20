<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izdt5_wln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="izdt5_wln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:media-skip-forward" /></template>
