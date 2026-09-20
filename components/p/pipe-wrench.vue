<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0c0eu8vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0c0eu8vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pipe-wrench" /></template>
