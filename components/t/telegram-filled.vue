<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1a2adbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m1a2adbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:telegram-filled" /></template>
