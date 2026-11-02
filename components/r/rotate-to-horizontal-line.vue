<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1degvmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1degvmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rotate-to-horizontal-line" /></template>
