<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1_nwk66w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1_nwk66w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:stairs-arrow-down-left" /></template>
