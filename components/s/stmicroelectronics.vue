<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvj03-vyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvj03-vyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:stmicroelectronics" /></template>
