<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2h3tpbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o2h3tpbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:web-remix" /></template>
