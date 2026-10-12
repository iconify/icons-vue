<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxzfl5btn.css';
import '../../css/e/ekw862bgh.css';
import '../../css/d/d8p7d1b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lxzfl5btn"/><path class="ekw862bgh"/><path class="d8p7d1b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paste-48" /></template>
