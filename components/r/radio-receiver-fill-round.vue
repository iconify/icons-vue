<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygo64bceg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygo64bceg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-receiver-fill-round" /></template>
