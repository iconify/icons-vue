<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2do7bc4s.css';
import '../../css/k/kue68edpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w2do7bc4s"/><path class="kue68edpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:restaurant-outline" /></template>
