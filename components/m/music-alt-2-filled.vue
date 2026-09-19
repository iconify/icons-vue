<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfc3x4wxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfc3x4wxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:music-alt-2-filled" /></template>
