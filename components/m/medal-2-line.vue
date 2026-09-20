<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqqnoyl3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqqnoyl3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:medal-2-line" /></template>
