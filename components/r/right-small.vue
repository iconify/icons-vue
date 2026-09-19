<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az-5w-ucj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="az-5w-ucj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:right-small" /></template>
