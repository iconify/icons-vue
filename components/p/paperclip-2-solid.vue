<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdd6--buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdd6--buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:paperclip-2-solid" /></template>
