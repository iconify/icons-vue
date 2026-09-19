<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1p-v2bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z1p-v2bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-full" /></template>
