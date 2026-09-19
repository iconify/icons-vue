<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s09wq-brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s09wq-brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:move-left" /></template>
