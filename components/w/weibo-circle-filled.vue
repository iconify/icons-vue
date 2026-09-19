<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j317_ccvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j317_ccvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:weibo-circle-filled" /></template>
