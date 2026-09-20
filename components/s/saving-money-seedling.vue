<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rmzlaacmz.css';
import '../../css/u/uc0ced3xe.css';
import '../../css/y/yt_spx0-o.css';
import '../../css/f/fjf51v-lh.css';
import '../../css/e/elx-v3mgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rmzlaacmz"/><path class="uc0ced3xe"/><path class="yt_spx0-o"/><path class="fjf51v-lh"/><path class="elx-v3mgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:saving-money-seedling" /></template>
