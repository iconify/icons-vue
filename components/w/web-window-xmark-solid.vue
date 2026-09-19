<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7i78vbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7i78vbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:web-window-xmark-solid" /></template>
