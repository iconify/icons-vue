<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twr408bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="twr408bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:menu-fold" /></template>
