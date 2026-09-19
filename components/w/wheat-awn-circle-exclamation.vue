<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um1cdwptq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="um1cdwptq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:wheat-awn-circle-exclamation" /></template>
