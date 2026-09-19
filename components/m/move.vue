<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2twb1bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q2twb1bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:move" /></template>
