<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-ali6xtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i-ali6xtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-search-remix" /></template>
