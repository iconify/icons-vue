<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2-qpdbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w2-qpdbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:toilet-man-remix" /></template>
