<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe4svgg5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fe4svgg5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:video-camera-filled" /></template>
