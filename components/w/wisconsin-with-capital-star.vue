<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yndpv1bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yndpv1bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wisconsin-with-capital-star" /></template>
