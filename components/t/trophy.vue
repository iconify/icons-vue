<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxsqdsmyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxsqdsmyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:trophy" /></template>
