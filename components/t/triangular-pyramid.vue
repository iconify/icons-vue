<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex2k96bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ex2k96bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:triangular-pyramid" /></template>
