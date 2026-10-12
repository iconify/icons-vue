<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kze1e9b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kze1e9b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-color-stroke-20" /></template>
