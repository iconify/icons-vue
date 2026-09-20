<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huaop5l8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="huaop5l8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:soundcloud" /></template>
