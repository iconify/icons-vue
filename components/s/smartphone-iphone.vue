<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3-7xhb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":280,"height":480};
const content = `<path class="y3-7xhb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-iphone" /></template>
