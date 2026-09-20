<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cht72sbxm.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/av3m8fbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGviYHfcjm" class="cht72sbxm"/></defs><g class="ft5dv1b6b"><use href="#SVGviYHfcjm"/><use href="#SVGviYHfcjm" class="av3m8fbrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tower-2" /></template>
