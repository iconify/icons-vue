<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2a7yabmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2a7yabmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:onestream" /></template>
