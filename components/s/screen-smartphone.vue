<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy3_k6b3r.css';
import '../../css/z/z-jza3xhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vy3_k6b3r"/><path class="z-jza3xhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:screen-smartphone" /></template>
