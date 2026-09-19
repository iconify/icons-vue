<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wygaw9brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wygaw9brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:open-a-i-outlined" /></template>
