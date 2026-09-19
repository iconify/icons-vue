<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvcwa-j2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yvcwa-j2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:podcast" /></template>
