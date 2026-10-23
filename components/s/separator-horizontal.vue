<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhf967wag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhf967wag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:separator-horizontal" /></template>
