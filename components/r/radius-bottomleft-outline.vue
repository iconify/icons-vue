<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szt_gcbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="szt_gcbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:radius-bottomleft-outline" /></template>
