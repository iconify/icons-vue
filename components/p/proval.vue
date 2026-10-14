<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qempt5bxh.css';
import '../../css/e/e7pfvbb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qempt5bxh"/><path class="e7pfvbb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proval" /></template>
