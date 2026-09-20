<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk989y3dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jk989y3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:smoking-area-remix" /></template>
