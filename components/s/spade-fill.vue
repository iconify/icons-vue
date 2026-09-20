<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g63kmynmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g63kmynmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:spade-fill" /></template>
