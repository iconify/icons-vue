<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu_-mhben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu_-mhben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stadium-outline" /></template>
