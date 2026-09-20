<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zja1g2tpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zja1g2tpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:time-zone-fill" /></template>
