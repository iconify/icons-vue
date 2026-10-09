<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6nfsjb9y.css';
import '../../css/q/qotc-vbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r6nfsjb9y"/><path class="qotc-vbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-grid-48-bold" /></template>
