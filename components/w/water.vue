<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i81xwnbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i81xwnbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:water" /></template>
