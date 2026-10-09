<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkarr2bij.css';
import '../../css/k/k6ocuztoi.css';
import '../../css/g/gv5tz0b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kkarr2bij"/><path class="k6ocuztoi"/><path class="gv5tz0b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:socket-48-bold" /></template>
