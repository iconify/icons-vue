<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whm6_wb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="whm6_wb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:tailless-line-arrow-right-circle-remix" /></template>
