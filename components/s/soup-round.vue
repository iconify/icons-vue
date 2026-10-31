<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl2ya4fxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl2ya4fxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:soup-round" /></template>
