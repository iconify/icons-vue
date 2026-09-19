<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba83d045k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ba83d045k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:worker" /></template>
