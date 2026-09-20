<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp4964afi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fp4964afi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:supermarket-cart" /></template>
