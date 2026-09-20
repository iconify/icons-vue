<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx6um9bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wx6um9bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:stock-remix" /></template>
