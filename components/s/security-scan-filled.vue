<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j48_gdb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j48_gdb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:security-scan-filled" /></template>
