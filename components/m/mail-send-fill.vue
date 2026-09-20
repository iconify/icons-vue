<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr0ponqtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jr0ponqtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-send-fill" /></template>
