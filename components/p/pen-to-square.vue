<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsq8u9wdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fsq8u9wdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pen-to-square" /></template>
