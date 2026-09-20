<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xriey6b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="xriey6b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:tag-milestone" /></template>
