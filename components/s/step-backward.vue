<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks99qt2hl.css';
import '../../css/e/eh8-ivaqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks99qt2hl"/><path class="eh8-ivaqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:step-backward" /></template>
