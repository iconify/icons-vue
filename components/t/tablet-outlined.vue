<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xad1hdcaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xad1hdcaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:tablet-outlined" /></template>
