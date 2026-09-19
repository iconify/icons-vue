<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i79c0yxye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i79c0yxye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:yelp" /></template>
