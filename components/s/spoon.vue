<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhijw3bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zhijw3bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:spoon" /></template>
