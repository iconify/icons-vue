<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q40h8-b-p.css';
import '../../css/w/wu_emw7zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q40h8-b-p"/><path class="wu_emw7zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:run-of-river-48-bold" /></template>
