<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rktte6bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rktte6bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:terminal" /></template>
