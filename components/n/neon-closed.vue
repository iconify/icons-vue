<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5tpc4bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5tpc4bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:neon-closed" /></template>
