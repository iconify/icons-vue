<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oku93bowu.css';
import '../../css/p/p2-gc3lvi.css';
import '../../css/n/nzvyk8_7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oku93bowu"/><path class="p2-gc3lvi"/><path class="nzvyk8_7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-search-48-bold" /></template>
