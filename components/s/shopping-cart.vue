<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/j/jec50dbaz.css';
import '../../css/b/bqu-4jb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jec50dbaz"/><path class="bqu-4jb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:shopping-cart" /></template>
