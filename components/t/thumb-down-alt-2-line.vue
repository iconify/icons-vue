<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxfgdi9_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxfgdi9_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:thumb-down-alt-2-line" /></template>
