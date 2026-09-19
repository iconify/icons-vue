<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gadlvgwmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="gadlvgwmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:water-ladder" /></template>
