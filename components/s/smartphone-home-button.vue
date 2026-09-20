<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/il7wpu91y.css';
import '../../css/m/mh3pkcc1w.css';
import '../../css/b/bbyl-z2kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="il7wpu91y"/><path clip-rule="evenodd" class="mh3pkcc1w"/><path class="bbyl-z2kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:smartphone-home-button" /></template>
