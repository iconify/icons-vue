<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnb_aj5jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="jnb_aj5jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tv-play" /></template>
