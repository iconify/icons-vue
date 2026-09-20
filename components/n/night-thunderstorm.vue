<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uymhvmb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="uymhvmb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-thunderstorm" /></template>
