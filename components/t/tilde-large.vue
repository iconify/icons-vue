<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzrv9qbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hzrv9qbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tilde-large" /></template>
