<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1_hfx2hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1_hfx2hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:space-station" /></template>
