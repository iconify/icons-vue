<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do32_5buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="do32_5buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pencil-circle-remix" /></template>
