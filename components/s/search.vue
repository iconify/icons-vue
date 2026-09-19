<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqhlyfbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rqhlyfbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:search" /></template>
