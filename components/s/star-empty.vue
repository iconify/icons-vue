<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft1yr5mlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ft1yr5mlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:star-empty" /></template>
