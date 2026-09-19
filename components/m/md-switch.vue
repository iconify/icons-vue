<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq0gx_bgt.css';
import '../../css/w/w6a568a7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fq0gx_bgt"/><path class="w6a568a7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-switch" /></template>
