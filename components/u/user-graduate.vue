<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyoctf0bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eyoctf0bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-graduate" /></template>
