<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3d55nbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h3d55nbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:shopping-cart-solid" /></template>
