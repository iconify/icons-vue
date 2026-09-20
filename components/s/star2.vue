<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eylr1q3ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eylr1q3ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:star2" /></template>
