<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv2331gbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yv2331gbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:viadeo" /></template>
