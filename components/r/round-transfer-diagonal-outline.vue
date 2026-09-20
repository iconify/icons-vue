<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6e8x3psq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6e8x3psq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-transfer-diagonal-outline" /></template>
