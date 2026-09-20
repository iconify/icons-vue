<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/y-sfj2bgs.css';
import '../../css/n/n5c-clmjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="y-sfj2bgs"/><path class="n5c-clmjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:map-marker-5" /></template>
