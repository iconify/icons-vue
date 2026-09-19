<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlfcf80ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tlfcf80ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-down-filled-alt" /></template>
