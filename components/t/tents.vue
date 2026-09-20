<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhoh9byhl.css';
import '../../css/g/gca746gmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jhoh9byhl"/><path class="gca746gmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tents" /></template>
