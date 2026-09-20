<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmaew0blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wmaew0blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sunrise-fill" /></template>
