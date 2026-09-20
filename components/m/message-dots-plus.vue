<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i_nkn0mxa.css';
import '../../css/e/e2y-qsboe.css';
import '../../css/j/jm98hmxlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i_nkn0mxa"/><path class="e2y-qsboe"/><path class="jm98hmxlc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-dots-plus" /></template>
