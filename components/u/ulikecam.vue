<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd9390eio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nd9390eio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:ulikecam" /></template>
