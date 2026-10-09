<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgxm3zihq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sgxm3zihq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skip-forward-48-bold" /></template>
