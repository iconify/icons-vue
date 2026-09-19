<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtbrppwwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mtbrppwwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:press" /></template>
