<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exdltnb9b.css';
import '../../css/r/rg-moybam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="exdltnb9b"/><path class="rg-moybam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:offline-gateway-filled" /></template>
