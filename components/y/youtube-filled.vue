<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctk7unbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ctk7unbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:youtube-filled" /></template>
