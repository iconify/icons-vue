<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0mjxcc0d.css';
import '../../css/i/icy1kprcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0mjxcc0d"/><path clip-rule="evenodd" class="icy1kprcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tips" /></template>
