<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5_uatzam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s5_uatzam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:paint-palette-solid" /></template>
