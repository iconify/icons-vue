<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkdf8eh1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hkdf8eh1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:restaurant-14" /></template>
