<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf363obkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sf363obkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:xing-square" /></template>
