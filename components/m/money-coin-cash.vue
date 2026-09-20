<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cke6vwbrd.css';
import '../../css/k/kbp6v8_4a.css';
import '../../css/w/w3q6r8btx.css';
import '../../css/i/i8t5fzqma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cke6vwbrd"/><path class="kbp6v8_4a"/><path class="w3q6r8btx"/><path class="i8t5fzqma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:money-coin-cash" /></template>
