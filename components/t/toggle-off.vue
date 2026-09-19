<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtjcexbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jtjcexbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:toggle-off" /></template>
