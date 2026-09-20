<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws8evmb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws8evmb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:server-off" /></template>
