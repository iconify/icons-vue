<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh3iejbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gh3iejbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:spanner" /></template>
