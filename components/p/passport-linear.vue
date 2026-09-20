<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rap11obza.css';
import '../../css/f/fr_tmn9fp.css';
import '../../css/g/ga7t0girt.css';
import '../../css/c/chuhguiil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rap11obza"/><circle class="fr_tmn9fp"/><path class="ga7t0girt"/><path class="chuhguiil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:passport-linear" /></template>
