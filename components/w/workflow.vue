<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idyw_vbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idyw_vbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:workflow" /></template>
