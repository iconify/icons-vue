<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbxlvlbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mbxlvlbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pen-1-remix" /></template>
