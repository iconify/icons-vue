<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkq3vx3ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkq3vx3ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-cart-1-fill" /></template>
