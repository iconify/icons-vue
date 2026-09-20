<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewflq-bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewflq-bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:snapchat-logo" /></template>
