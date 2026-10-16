<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccnocllyv.css';
import '../../css/e/eb4h0cb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ccnocllyv"/><path class="eb4h0cb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkline-20" /></template>
