<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryotqrb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ryotqrb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:panoramic-screen-remix" /></template>
