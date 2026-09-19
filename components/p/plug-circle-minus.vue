<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l82wo8b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="l82wo8b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:plug-circle-minus" /></template>
