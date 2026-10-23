<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nui_d4bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nui_d4bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scaling" /></template>
