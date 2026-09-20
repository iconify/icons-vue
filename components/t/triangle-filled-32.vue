<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af4lzgb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="af4lzgb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:triangle-filled-32" /></template>
