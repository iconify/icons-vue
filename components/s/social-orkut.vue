<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/f0e2grbjh.css';
import '../../css/z/z9bc0ktrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="f0e2grbjh"/><path class="z9bc0ktrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-orkut" /></template>
