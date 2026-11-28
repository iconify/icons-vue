<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpc_mmbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpc_mmbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wand-check" /></template>
