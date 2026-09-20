<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzow1dvyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uzow1dvyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:send-twice-square-bold" /></template>
