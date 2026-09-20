<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz3q-gb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nz3q-gb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-podcast-remix" /></template>
