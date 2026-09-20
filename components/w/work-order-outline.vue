<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgq75lbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lgq75lbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:work-order-outline" /></template>
