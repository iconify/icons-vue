<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i23u8pb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i23u8pb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:umbrella" /></template>
