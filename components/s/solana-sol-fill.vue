<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsbf2wbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wsbf2wbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:solana-sol-fill" /></template>
