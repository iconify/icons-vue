<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw2ojp_cc.css';
import '../../css/e/e04op1bwe.css';
import '../../css/g/gutycobgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bw2ojp_cc"/><path class="e04op1bwe"/><path class="gutycobgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediamanager-dark" /></template>
