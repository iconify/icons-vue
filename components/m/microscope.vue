<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/uznrkyg-i.css';
import '../../css/w/wwhz16b1f.css';
import '../../css/n/n3l509bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uznrkyg-i"/><path class="wwhz16b1f"/><path class="n3l509bcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:microscope" /></template>
