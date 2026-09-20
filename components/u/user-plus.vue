<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-92lpsuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n-92lpsuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-plus" /></template>
