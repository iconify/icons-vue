<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9n0gb6of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d9n0gb6of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:up-and-down" /></template>
