<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfkp55bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfkp55bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:stitcher-logo-1-solid" /></template>
