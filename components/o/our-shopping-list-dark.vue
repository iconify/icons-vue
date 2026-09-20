<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri15mwhnp.css';
import '../../css/q/qjx3e9jap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ri15mwhnp"/><path class="qjx3e9jap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:our-shopping-list-dark" /></template>
