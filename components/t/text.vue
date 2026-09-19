<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_w0ioocj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_w0ioocj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:text" /></template>
