<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/mc8rtl3wh.css';
import '../../css/b/b8uh54bhe.css';
import '../../css/c/chh9m8bfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mc8rtl3wh"/><path class="b8uh54bhe"/><path class="chh9m8bfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wifi-medium-sharp-duotone" /></template>
