<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/mzxv1bbpg.css';
import '../../css/t/t135zx7nc.css';
import '../../css/v/vbcgq2ytz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mzxv1bbpg"/><path class="t135zx7nc"/><path class="vbcgq2ytz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:water-broken" /></template>
