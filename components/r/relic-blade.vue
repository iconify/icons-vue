<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axk8kbb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="axk8kbb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:relic-blade" /></template>
