<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iycln-b8i.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/y/y02hk3jmi.css';
import '../../css/s/samcq3xfd.css';
import '../../css/m/m9vsufp9g.css';
import '../../css/u/udmajcboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><circle id="SVG1g8rabco" class="iycln-b8i"/></defs><clipPath id="SVGJdal8dOW"><use href="#SVG1g8rabco"/></clipPath><g clip-path="url(#SVGJdal8dOW)" class="n1mjunbsu"><path class="y02hk3jmi"/><path class="samcq3xfd"/><path class="m9vsufp9g"/><path class="udmajcboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ollama-light" /></template>
