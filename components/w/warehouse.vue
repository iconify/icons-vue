<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6p6cebil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="y6p6cebil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:warehouse" /></template>
