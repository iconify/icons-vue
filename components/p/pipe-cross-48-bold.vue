<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jycek3qdf.css';
import '../../css/a/aow2a9b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jycek3qdf"/><path class="aow2a9b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-cross-48-bold" /></template>
