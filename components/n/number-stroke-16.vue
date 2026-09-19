<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tynb5sbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tynb5sbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:number-stroke-16" /></template>
