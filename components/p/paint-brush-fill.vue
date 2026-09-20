<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecex6lblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ecex6lblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paint-brush-fill" /></template>
