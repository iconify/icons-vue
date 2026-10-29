<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/nrlirxy2k.css';
import '../../css/y/yxavwr9yf.css';
import '../../css/f/fle9zy2qg.css';
import '../../css/m/mn3s37b7a.css';
import '../../css/n/n4g7kqb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="nrlirxy2k wm-deco"/><path class="wm-deco yxavwr9yf"/><path class="fle9zy2qg wm-deco"/><path class="mn3s37b7a"/><path class="n4g7kqb8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wifi-low-blueprint" /></template>
