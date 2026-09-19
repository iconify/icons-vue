<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3bxpab3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y3bxpab3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:peso-sign" /></template>
