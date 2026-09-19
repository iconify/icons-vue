<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7xu5rhoq.css';
import '../../css/u/uqr-rtqnv.css';
import '../../css/r/rbwpa9bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="z7xu5rhoq"/><path class="uqr-rtqnv"/><path class="rbwpa9bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:query" /></template>
