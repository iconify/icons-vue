<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we5jwd_ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="we5jwd_ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:puzzle" /></template>
