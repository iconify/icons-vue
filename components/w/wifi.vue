<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmyfs8bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rmyfs8bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:wifi" /></template>
