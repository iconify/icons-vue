<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esxr-xbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esxr-xbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unhappy-dizzy-fill" /></template>
