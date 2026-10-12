<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su-w6wf-n.css';
import '../../css/q/qvm9k_b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="su-w6wf-n"/><path class="qvm9k_b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-can-48" /></template>
