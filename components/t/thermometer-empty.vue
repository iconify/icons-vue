<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-u__lkge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f-u__lkge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:thermometer-empty" /></template>
