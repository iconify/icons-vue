<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1a2-qbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1a2-qbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:volume-off-vibrate-line" /></template>
