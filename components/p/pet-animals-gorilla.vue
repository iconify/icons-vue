<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxtlembsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vxtlembsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:pet-animals-gorilla" /></template>
