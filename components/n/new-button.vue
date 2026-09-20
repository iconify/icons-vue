<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk-o4xbvq.css';
import '../../css/l/lbifckknp.css';
import '../../css/t/tng-zhj-p.css';
import '../../css/a/akhdmbcky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<rect transform="translate(0 -.014)" class="xk-o4xbvq"/><g transform="translate(0 -.014)" class="lbifckknp"><path clip-rule="evenodd" class="tng-zhj-p"/><rect class="akhdmbcky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:new-button" /></template>
