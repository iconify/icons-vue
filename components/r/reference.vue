<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pfxmy0brn.css';
import '../../css/m/mro1p6pmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="n1lsf0bnc"><path class="pfxmy0brn"/><path class="mro1p6pmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:reference" /></template>
