<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuw49scvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vuw49scvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-off-filled" /></template>
