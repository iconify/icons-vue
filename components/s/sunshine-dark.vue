<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grfi6tbpu.css';
import '../../css/w/w2h3d0buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="grfi6tbpu"/><path class="w2h3d0buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sunshine-dark" /></template>
