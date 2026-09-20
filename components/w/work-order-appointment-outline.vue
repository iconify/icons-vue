<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy072qbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vy072qbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:work-order-appointment-outline" /></template>
