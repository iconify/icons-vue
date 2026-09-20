<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l--ug-2eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l--ug-2eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:volume-level-high-remix" /></template>
