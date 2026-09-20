<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nne87hv2x.css';
import '../../css/b/bfaiweb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nne87hv2x"/><path class="bfaiweb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:monitor-code" /></template>
