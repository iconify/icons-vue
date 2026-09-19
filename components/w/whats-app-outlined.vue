<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztm4cfb3x.css';
import '../../css/r/rx-beboiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ztm4cfb3x"/><path class="rx-beboiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:whats-app-outlined" /></template>
