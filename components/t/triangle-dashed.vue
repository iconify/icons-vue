<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxut5rbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxut5rbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-dashed" /></template>
