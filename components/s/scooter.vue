<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwp6e0bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hwp6e0bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:scooter" /></template>
