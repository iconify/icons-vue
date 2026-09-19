<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrg8lz20a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mrg8lz20a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:square" /></template>
