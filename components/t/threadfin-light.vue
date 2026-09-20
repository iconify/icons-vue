<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xus3r2plp.css';
import '../../css/o/orv7ykb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xus3r2plp"/><path class="orv7ykb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:threadfin-light" /></template>
