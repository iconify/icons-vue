<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk29gcbsq.css';
import '../../css/k/ktus5xkah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qk29gcbsq"/><path clip-rule="evenodd" class="ktus5xkah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pdf-solid" /></template>
