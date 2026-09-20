<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnwh4p25o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tnwh4p25o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:wave-signal-circle-solid" /></template>
