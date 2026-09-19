<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk4c0x2at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk4c0x2at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:strikethrough" /></template>
