<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/l28f2kn4r.css';
import '../../css/i/i86kzcqeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="l28f2kn4r"/><path class="i86kzcqeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:planet-ring" /></template>
