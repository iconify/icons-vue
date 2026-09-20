<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p068o5acv.css';
import '../../css/s/sm2nqnaxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p068o5acv"/><path class="sm2nqnaxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pic-ai-line" /></template>
