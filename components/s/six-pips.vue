<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0pww9bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t0pww9bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:six-pips" /></template>
