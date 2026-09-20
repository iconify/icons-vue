<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msg05sbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="msg05sbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:octagram-shape-remix" /></template>
