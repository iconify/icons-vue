<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qylradd1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qylradd1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tortoise" /></template>
