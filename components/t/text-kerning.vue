<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvhkvnbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nvhkvnbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-kerning" /></template>
