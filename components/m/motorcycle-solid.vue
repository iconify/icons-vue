<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w03_zbzhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w03_zbzhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:motorcycle-solid" /></template>
