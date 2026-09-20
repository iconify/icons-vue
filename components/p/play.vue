<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etk300bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="etk300bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:play" /></template>
