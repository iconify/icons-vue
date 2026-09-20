<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqzar5xlv.css';
import '../../css/e/eo4l80r5n.css';
import '../../css/n/nd0_hkbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="zqzar5xlv"/><path class="eo4l80r5n"/><path class="nd0_hkbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openuem" /></template>
