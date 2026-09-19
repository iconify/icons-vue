<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixu4zybsc.css';
import '../../css/a/a23i8nphm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixu4zybsc"/><path class="a23i8nphm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:nopedestrians" /></template>
