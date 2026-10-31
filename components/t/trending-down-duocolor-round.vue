<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0g1dmd3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0g1dmd3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-down-duocolor-round" /></template>
