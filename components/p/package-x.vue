<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t15hl03kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t15hl03kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:package-x" /></template>
