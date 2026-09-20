<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po87b7bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="po87b7bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pen-tool-remix" /></template>
