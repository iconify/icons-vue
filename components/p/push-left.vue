<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pms-68f9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="pms-68f9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:push-left" /></template>
