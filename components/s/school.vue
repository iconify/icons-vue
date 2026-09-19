<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjp2ig6jr.css';
import '../../css/m/mch78aboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qjp2ig6jr"/><path class="mch78aboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:school" /></template>
