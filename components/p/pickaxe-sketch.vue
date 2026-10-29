<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z_pfq4bwn.css';
import '../../css/k/krxz-acfd.css';
import '../../css/z/zs3_58bis.css';
import '../../css/e/e9z8zubjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z_pfq4bwn"/><path class="krxz-acfd wm-k"/><path class="wm-k zs3_58bis"/><path class="e9z8zubjt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pickaxe-sketch" /></template>
