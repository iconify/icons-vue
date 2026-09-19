<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os2lqsv0d.css';
import '../../css/i/intfgbexo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os2lqsv0d"/><path class="intfgbexo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tachometer" /></template>
