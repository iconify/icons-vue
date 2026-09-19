<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm11y1rnv.css';
import '../../css/c/cmgsz-b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jm11y1rnv"/><path class="cmgsz-b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-journal" /></template>
