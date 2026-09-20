<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tigutsb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tigutsb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:volume3" /></template>
