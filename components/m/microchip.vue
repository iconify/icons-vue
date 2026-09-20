<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i04rcb0gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i04rcb0gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:microchip" /></template>
