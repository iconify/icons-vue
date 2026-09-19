<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk0rmxbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lk0rmxbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:star-fill-12" /></template>
