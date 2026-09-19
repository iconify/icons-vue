<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo-ispbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bo-ispbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:parabola" /></template>
