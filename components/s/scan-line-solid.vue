<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmrq8iauz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmrq8iauz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scan-line-solid" /></template>
