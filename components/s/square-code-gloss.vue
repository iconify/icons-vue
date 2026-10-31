<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmux3-dwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmux3-dwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:square-code-gloss" /></template>
