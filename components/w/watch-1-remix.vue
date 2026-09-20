<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_1mxbb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w_1mxbb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:watch-1-remix" /></template>
