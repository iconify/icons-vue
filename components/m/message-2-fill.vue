<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viotswb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="viotswb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-2-fill" /></template>
