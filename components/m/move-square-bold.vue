<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joa8-ubia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="joa8-ubia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-square-bold" /></template>
