<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnx-vib2x.css';
import '../../css/i/irjsvsbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnx-vib2x"/><path class="irjsvsbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:message-rounded-detail" /></template>
