<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3qj_ibrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o3qj_ibrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:work-order-check-outline" /></template>
