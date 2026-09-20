<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omeiwubuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="omeiwubuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:no-photo-taking-zone-flat" /></template>
