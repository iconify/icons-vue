<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifp1qh_-h.css';
import '../../css/w/wfx3nk7mg.css';
import '../../css/m/mzbpuy9cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ifp1qh_-h"/><path class="wfx3nk7mg"/><path class="mzbpuy9cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scour-protection-48" /></template>
