<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu2nr00zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu2nr00zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:palette-1-filled" /></template>
