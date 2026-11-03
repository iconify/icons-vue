<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp6svgb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cp6svgb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pill-20-solid" /></template>
