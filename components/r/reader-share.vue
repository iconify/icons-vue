<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7vvir64i.css';
import '../../css/r/roi1-go0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<clipPath id="SVGWLziubJw"><path class="t7vvir64i"/></clipPath><g clip-path="url(#SVGWLziubJw)"><path class="roi1-go0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:reader-share" /></template>
