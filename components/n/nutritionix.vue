<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj4jtmo4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wj4jtmo4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:nutritionix" /></template>
