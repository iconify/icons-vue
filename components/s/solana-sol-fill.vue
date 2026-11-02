<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6y9l9blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6y9l9blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:solana-sol-fill" /></template>
