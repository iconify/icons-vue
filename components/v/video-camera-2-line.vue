<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aad6nz3iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aad6nz3iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:video-camera-2-line" /></template>
