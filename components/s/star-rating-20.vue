<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg5jh0yog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vg5jh0yog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-rating-20" /></template>
