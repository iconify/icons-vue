<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khy_1bp6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="khy_1bp6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:scanning" /></template>
