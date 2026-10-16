<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df4gvuaqr.css';
import '../../css/f/friicz-ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="df4gvuaqr"/><path class="friicz-ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-reducer-48" /></template>
