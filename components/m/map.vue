<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc46zh7yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sc46zh7yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:map" /></template>
