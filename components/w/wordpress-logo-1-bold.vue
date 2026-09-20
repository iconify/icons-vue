<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llucre1fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llucre1fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:wordpress-logo-1-bold" /></template>
