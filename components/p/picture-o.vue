<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv7-5d-vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1536};
const content = `<path class="qv7-5d-vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:picture-o" /></template>
