<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vjf2x3b9w.css';
import '../../css/j/jxeobwgmm.css';
import '../../css/a/ahzs3cris.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vjf2x3b9w"/><path class="jxeobwgmm"/><path class="ahzs3cris"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-pinned" /></template>
