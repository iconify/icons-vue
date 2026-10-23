<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a85bfdc6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a85bfdc6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:move-vertical" /></template>
