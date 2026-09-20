<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayplkqblz.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b7o7pybje.css';
import '../../css/s/s_sytbc_y.css';
import '../../css/v/vps93z20j.css';
import '../../css/d/d2kvgvbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGBCtSOchg" class="ayplkqblz"/></defs><g class="cuyn6tgcc"><path clip-rule="evenodd" class="b7o7pybje"/><use href="#SVGBCtSOchg"/><path clip-rule="evenodd" class="s_sytbc_y"/><path class="vps93z20j"/><use href="#SVGBCtSOchg" clip-rule="evenodd" class="d2kvgvbvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wallet-money" /></template>
