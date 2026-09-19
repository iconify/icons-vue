<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj8tm6bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cj8tm6bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:swap" /></template>
