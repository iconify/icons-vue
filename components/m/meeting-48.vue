<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6ws95bmc.css';
import '../../css/g/gtwn_2b4z.css';
import '../../css/l/lsfhf11ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e6ws95bmc"/><path class="gtwn_2b4z"/><path class="lsfhf11ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:meeting-48" /></template>
