<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hta0mxbau.css';
import '../../css/n/nbfqlubre.css';
import '../../css/s/s_9sokbmc.css';
import '../../css/t/txy0qobnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="hta0mxbau"/><circle class="nbfqlubre"/><circle class="s_9sokbmc"/><path class="txy0qobnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:music-artist-duotone" /></template>
