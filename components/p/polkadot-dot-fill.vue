<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvvtsgrrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvvtsgrrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:polkadot-dot-fill" /></template>
