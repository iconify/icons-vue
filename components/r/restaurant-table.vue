<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4i0v4m3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4i0v4m3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:restaurant-table" /></template>
