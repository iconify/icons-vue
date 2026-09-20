<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an5sm2bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="an5sm2bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:move-cross-over" /></template>
