<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcjn2w3es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcjn2w3es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:spade-filled" /></template>
