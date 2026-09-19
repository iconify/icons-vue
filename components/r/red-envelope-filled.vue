<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc02u_bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc02u_bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:red-envelope-filled" /></template>
