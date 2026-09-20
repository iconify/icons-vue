<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb800tpmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vb800tpmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:tailless-line-arrow-up-2-remix" /></template>
