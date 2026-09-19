<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv7qrfb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uv7qrfb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:uikit" /></template>
