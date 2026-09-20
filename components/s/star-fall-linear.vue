<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/p-w3owbpc.css';
import '../../css/w/wk0yq0bkm.css';
import '../../css/e/eak60cb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p-w3owbpc"/><path class="wk0yq0bkm"/><path class="eak60cb8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-linear" /></template>
