<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb0re9w3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mb0re9w3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:polaroid-remix" /></template>
