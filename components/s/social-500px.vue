<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/ge-usbc4v.css';
import '../../css/h/h18c3wshh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ge-usbc4v"/><path class="h18c3wshh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-500px" /></template>
