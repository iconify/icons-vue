<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf5fmya5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lf5fmya5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pennant" /></template>
