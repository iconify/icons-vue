<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/b/bm8u3rb-m.css';
import '../../css/z/zviecfb4g.css';
import '../../css/d/dcgw77bis.css';
import '../../css/c/ck7asmbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="bm8u3rb-m"/><circle class="zviecfb4g"/><circle class="dcgw77bis"/><circle class="ck7asmbky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:password-outline" /></template>
