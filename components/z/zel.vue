<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wveq9ybec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wveq9ybec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:zel" /></template>
