<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sig6v4bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sig6v4bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:shop-outlined" /></template>
