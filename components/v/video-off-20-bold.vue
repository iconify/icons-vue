<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx0rv7bbf.css';
import '../../css/k/khdf871ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xx0rv7bbf"/><path class="khdf871ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:video-off-20-bold" /></template>
