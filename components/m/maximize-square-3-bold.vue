<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivgsmkbsz.css';
import '../../css/x/x_vwkib6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivgsmkbsz"/><path clip-rule="evenodd" class="x_vwkib6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-3-bold" /></template>
