<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp1zz_b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp1zz_b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:solana-sol-line" /></template>
