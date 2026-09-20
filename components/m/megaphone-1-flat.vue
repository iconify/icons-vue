<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/u8h1n0bqe.css';
import '../../css/f/fptm9e5bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="u8h1n0bqe"/><path class="fptm9e5bd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:megaphone-1-flat" /></template>
