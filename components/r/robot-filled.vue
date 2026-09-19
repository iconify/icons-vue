<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yovewwbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yovewwbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:robot-filled" /></template>
