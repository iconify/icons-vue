<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn9d0ybci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hn9d0ybci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:setting-filled" /></template>
