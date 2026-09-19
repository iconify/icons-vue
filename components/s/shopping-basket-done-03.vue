<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr_8_8m1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr_8_8m1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-basket-done-03" /></template>
