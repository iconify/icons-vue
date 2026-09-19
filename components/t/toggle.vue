<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc-j51bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gc-j51bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:toggle" /></template>
