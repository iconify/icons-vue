<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nco9j1bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nco9j1bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:printer-fill" /></template>
