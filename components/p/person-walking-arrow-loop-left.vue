<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z48inlb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="z48inlb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-walking-arrow-loop-left" /></template>
