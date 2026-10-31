<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvvzo3brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvvzo3brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-close-round" /></template>
