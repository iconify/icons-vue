<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/sqi5mdecy.css';
import '../../css/g/gg9oyuvyf.css';
import '../../css/g/gx3tdtbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sqi5mdecy"/><path class="gg9oyuvyf"/><path class="gx3tdtbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:share-location-02" /></template>
