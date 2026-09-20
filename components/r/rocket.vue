<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0wywzbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l0wywzbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rocket" /></template>
