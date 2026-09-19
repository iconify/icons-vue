<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzfn51xny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vzfn51xny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:translate" /></template>
