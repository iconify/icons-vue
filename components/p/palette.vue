<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0yp2jb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i0yp2jb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:palette" /></template>
