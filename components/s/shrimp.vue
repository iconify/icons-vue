<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s92qk0c1o.css';
import '../../css/i/i9l7f6f9f.css';
import '../../css/s/sj5y__bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s92qk0c1o"/><path class="i9l7f6f9f"/><path class="sj5y__bmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shrimp" /></template>
