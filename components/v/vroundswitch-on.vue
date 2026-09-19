<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am58adb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="am58adb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:vroundswitch-on" /></template>
