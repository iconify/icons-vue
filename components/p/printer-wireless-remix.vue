<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3_wk58bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t3_wk58bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:printer-wireless-remix" /></template>
