<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1o--8zmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f1o--8zmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:virtual-reality-remix" /></template>
