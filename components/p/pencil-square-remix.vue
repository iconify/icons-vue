<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doo09ibxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="doo09ibxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pencil-square-remix" /></template>
