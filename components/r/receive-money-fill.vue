<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz4x-hbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz4x-hbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:receive-money-fill" /></template>
