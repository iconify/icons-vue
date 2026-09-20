<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqzqczbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqzqczbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:paint-brush-line" /></template>
