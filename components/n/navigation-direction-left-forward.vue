<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/j/j3v39jmcl.css';
import '../../css/e/ezazlrbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="j3v39jmcl"/><path class="ezazlrbau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:navigation-direction-left-forward" /></template>
