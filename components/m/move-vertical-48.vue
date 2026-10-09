<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh9opkozm.css';
import '../../css/d/dc1ph1bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jh9opkozm"/><path class="dc1ph1bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-vertical-48" /></template>
