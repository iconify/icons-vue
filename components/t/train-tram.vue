<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v99ydnjao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="v99ydnjao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:train-tram" /></template>
