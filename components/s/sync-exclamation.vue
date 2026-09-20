<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu_w61bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu_w61bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:sync-exclamation" /></template>
