<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo6pl3bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mo6pl3bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:programming-browser-build-build-website-development-window-code-programming-web-backend-browser-dev" /></template>
