<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwwcfcbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwwcfcbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-minus" /></template>
