<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu8-imbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fu8-imbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:move-one" /></template>
