<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wovc_fb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="wovc_fb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:tumblr-rect" /></template>
