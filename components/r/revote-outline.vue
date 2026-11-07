<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo3mbbcpz.css';
import '../../css/z/zv6teybjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo3mbbcpz"/><path class="zv6teybjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:revote-outline" /></template>
