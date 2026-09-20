<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/ooy41dbxp.css';
import '../../css/z/z0g9z0bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="n1lsf0bnc"><path class="ooy41dbxp"/><path class="z0g9z0bil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:youtube" /></template>
