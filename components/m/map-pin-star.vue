<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iecwfablg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iecwfablg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pin-star" /></template>
