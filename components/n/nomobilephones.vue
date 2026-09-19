<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egi7t0uie.css';
import '../../css/v/vnh2invat.css';
import '../../css/i/ixbj2wbiv.css';
import '../../css/a/a23i8nphm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="egi7t0uie"/><path class="vnh2invat"/><path class="ixbj2wbiv"/><path class="a23i8nphm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:nomobilephones" /></template>
