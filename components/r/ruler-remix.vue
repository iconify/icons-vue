<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2sqt4boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d2sqt4boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ruler-remix" /></template>
