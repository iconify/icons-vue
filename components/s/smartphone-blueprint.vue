<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/dab644bei.css';
import '../../css/f/f22o3bcfn.css';
import '../../css/z/zn-73g1qe.css';
import '../../css/h/hkcj5-bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="dab644bei wm-deco"/><path class="f22o3bcfn wm-deco"/><path class="wm-k zn-73g1qe"/><path class="hkcj5-bst wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smartphone-blueprint" /></template>
