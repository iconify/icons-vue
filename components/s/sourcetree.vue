<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hctv6-d5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="hctv6-d5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:sourcetree" /></template>
