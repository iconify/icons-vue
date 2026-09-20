<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0bvf-bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t0bvf-bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:template-16" /></template>
