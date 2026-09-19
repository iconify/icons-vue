<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z88dnnb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z88dnnb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:up-circle-filled" /></template>
