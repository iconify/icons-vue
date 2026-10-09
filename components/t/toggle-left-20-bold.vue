<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atfdt7ybg.css';
import '../../css/l/lxmkcbctr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="atfdt7ybg"/><path class="lxmkcbctr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toggle-left-20-bold" /></template>
