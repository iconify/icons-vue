<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqgv6xbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rqgv6xbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mpeg" /></template>
