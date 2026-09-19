<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu33pmb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uu33pmb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vintage-mac" /></template>
