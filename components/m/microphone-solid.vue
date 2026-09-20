<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9_uklbjc.css';
import '../../css/p/pv-24ob8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t9_uklbjc"/><path class="pv-24ob8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:microphone-solid" /></template>
