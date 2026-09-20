<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie7ohsbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ie7ohsbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:travel-plane" /></template>
