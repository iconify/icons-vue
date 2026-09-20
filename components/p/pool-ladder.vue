<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6vf3kbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s6vf3kbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pool-ladder" /></template>
