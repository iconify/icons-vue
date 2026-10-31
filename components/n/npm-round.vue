<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv9tpdbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv9tpdbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:npm-round" /></template>
