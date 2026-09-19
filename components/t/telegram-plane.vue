<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/libpo1h3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="libpo1h3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:telegram-plane" /></template>
