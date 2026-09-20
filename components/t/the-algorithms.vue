<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoui6huvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoui6huvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:the-algorithms" /></template>
