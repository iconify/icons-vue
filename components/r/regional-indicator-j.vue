<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwico__yj.css';
import '../../css/h/htu6zoakn.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/u/usozxnbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGREWbgcXm" class="jwico__yj"/></defs><circle class="htu6zoakn"/><use href="#SVGREWbgcXm"/><g class="kdz4acc8r"><circle class="usozxnbrm"/><use href="#SVGREWbgcXm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:regional-indicator-j" /></template>
