<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pedr4_bjp.css';
import '../../css/w/wk04f5vlf.css';
import '../../css/o/o6pwbnxip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pedr4_bjp"/><path class="wk04f5vlf"/><path class="o6pwbnxip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:synchronous-condenser-48-bold" /></template>
