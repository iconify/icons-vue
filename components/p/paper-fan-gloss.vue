<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyjk9sblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyjk9sblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paper-fan-gloss" /></template>
