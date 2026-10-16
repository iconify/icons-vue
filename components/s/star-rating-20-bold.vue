<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdkl37ceg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xdkl37ceg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-rating-20-bold" /></template>
