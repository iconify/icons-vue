<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wad-esvma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wad-esvma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tachometer-alt-filled" /></template>
