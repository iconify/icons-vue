<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knu3qfbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="knu3qfbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:volume-down" /></template>
