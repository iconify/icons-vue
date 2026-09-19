<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa-h08bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sa-h08bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:moonrise" /></template>
