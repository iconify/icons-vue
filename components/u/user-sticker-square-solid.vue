<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tigxf2bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tigxf2bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-sticker-square-solid" /></template>
