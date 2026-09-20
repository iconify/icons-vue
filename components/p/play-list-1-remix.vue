<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x13w85bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x13w85bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:play-list-1-remix" /></template>
