<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8hlz4bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8hlz4bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-cart-48" /></template>
