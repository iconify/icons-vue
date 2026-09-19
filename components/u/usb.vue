<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0ctoy-5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d0ctoy-5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:usb" /></template>
