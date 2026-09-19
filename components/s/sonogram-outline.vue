<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trfw2zy9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="trfw2zy9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sonogram-outline" /></template>
