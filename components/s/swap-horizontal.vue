<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouk9fb6fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ouk9fb6fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:swap-horizontal" /></template>
