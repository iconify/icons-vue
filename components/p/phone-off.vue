<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvrp96bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mvrp96bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:phone-off" /></template>
