<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faxxu_v1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="faxxu_v1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shopping-cart-20-bold" /></template>
