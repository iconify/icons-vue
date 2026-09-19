<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti6j9ubny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ti6j9ubny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:play-reverse" /></template>
