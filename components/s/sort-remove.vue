<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5f48ybqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h5f48ybqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sort-remove" /></template>
