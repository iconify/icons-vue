<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk3m6-_kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rk3m6-_kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rock-slide" /></template>
