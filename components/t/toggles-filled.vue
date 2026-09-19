<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y75ybwfrp.css';
import '../../css/w/wmxza4_8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y75ybwfrp"/><path class="wmxza4_8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:toggles-filled" /></template>
