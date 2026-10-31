<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwpr0gbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwpr0gbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:npm-fill-round" /></template>
