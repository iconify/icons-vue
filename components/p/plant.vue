<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvg3bgb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvg3bgb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plant" /></template>
