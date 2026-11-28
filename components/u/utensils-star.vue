<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noiu_naty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noiu_naty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:utensils-star" /></template>
