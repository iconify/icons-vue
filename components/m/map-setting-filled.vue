<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqenu4b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqenu4b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-setting-filled" /></template>
