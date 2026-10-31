<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldgncw1xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldgncw1xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-fill-round" /></template>
