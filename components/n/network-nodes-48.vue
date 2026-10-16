<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4caingdq.css';
import '../../css/s/sy8emvbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e4caingdq"/><path class="sy8emvbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:network-nodes-48" /></template>
