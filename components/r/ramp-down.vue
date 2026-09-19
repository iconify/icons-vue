<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkv516bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkv516bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:ramp-down" /></template>
