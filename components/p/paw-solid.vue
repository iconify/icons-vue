<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2d-j64pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d2d-j64pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:paw-solid" /></template>
