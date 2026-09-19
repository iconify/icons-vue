<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5plgss1t.css';
import '../../css/r/r8af-vbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h5plgss1t"/><path class="r8af-vbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:trash" /></template>
