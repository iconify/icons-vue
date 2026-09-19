<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2_a8x_yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b2_a8x_yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:watson-machine-learning" /></template>
