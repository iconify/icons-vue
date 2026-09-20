<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmrm1ub4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qmrm1ub4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:triangle-arrow-curvy-up-down-2-remix" /></template>
