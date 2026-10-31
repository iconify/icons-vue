<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw-1bebar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw-1bebar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-edit-corner-fill-round" /></template>
