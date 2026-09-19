<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh9u8-bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vh9u8-bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:qrcode-outlined" /></template>
