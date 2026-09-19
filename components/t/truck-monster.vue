<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/x/x3ffeyb2c.css';
import '../../css/q/q33bbjb-k.css';
import '../../css/e/e05kljyix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x3ffeyb2c"/><path class="q33bbjb-k"/><path class="e05kljyix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:truck-monster" /></template>
