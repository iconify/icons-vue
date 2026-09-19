<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wev0scb4m.css';
import '../../css/m/mi0qv-kbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wev0scb4m"/><path class="mi0qv-kbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:trending-down-outline" /></template>
