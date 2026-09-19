<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t70u-q92z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t70u-q92z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:train-subway" /></template>
