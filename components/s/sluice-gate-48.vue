<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmzb4zr4b.css';
import '../../css/l/lbvcveb9f.css';
import '../../css/z/z2zx3vbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hmzb4zr4b"/><path class="lbvcveb9f"/><path class="z2zx3vbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sluice-gate-48" /></template>
