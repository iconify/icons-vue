<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mil61zbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mil61zbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tty" /></template>
