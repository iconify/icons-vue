<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i29phwzfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="i29phwzfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-remove-fill-12" /></template>
