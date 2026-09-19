<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tawrpdb4t.css';
import '../../css/m/mt3oabbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tawrpdb4t"/><path class="mt3oabbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medal-star" /></template>
