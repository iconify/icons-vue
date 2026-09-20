<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn2u72yrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yn2u72yrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:paint-roller" /></template>
