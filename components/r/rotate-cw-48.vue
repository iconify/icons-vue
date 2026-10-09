<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crskxccsk.css';
import '../../css/t/t_o6wlbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="crskxccsk"/><path class="t_o6wlbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotate-cw-48" /></template>
