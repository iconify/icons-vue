<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pxkklfxth.css';
import '../../css/u/uzm3_fbfh.css';
import '../../css/a/a2wio1sog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pxkklfxth"/><path class="uzm3_fbfh"/><path class="a2wio1sog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scan-eye-duotone" /></template>
