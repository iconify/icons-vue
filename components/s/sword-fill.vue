<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc-_0tbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cc-_0tbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sword-fill" /></template>
