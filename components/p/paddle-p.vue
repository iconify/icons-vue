<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifssrslal.css';
import '../../css/t/tdn_98ffj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifssrslal"/><path class="tdn_98ffj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:paddle-p" /></template>
