<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfv2xx_mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qfv2xx_mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:msbuild" /></template>
