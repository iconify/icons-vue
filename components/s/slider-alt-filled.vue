<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku-xu3yrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku-xu3yrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:slider-alt-filled" /></template>
