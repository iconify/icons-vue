<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd26ri4fm.css';
import '../../css/v/vn40uv8sr.css';
import '../../css/s/ssu0d0bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qd26ri4fm"/><path class="vn40uv8sr"/><path class="ssu0d0bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:rocket-twotone" /></template>
