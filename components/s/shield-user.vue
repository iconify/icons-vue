<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/ezzhmbj5r.css';
import '../../css/y/yfymg5b-i.css';
import '../../css/r/rus9pebka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ezzhmbj5r"/><path class="yfymg5b-i"/><circle class="rus9pebka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:shield-user" /></template>
