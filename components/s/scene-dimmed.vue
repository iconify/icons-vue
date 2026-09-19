<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbz_imbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbz_imbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:scene-dimmed" /></template>
