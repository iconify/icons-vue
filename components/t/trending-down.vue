<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu6gvgb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu6gvgb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trending-down" /></template>
