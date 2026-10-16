<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iszq-fbrp.css';
import '../../css/k/k3b73mscw.css';
import '../../css/i/i13dt1b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iszq-fbrp"/><path class="k3b73mscw"/><path class="i13dt1b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sluice-gate-48-bold" /></template>
