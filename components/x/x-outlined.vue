<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-aa569ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m-aa569ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:x-outlined" /></template>
