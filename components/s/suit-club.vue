<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjm8lsc9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gjm8lsc9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:suit-club" /></template>
