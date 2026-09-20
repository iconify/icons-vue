<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7u_32bvh.css';
import '../../css/x/x39yvob4g.css';
import '../../css/l/l105bfj4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGr77DHd6N" class="e7u_32bvh"/></defs><use href="#SVGr77DHd6N" class="x39yvob4g"/><use href="#SVGr77DHd6N" class="x39yvob4g"/><path class="l105bfj4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:send-duotone" /></template>
