<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i17321bsh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/as0h4gb1d.css';
import '../../css/n/nodmk3bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i17321bsh secondary"/><g class="dt0cm9dhy primary"><path class="as0h4gb1d"/><path class="nodmk3bfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sparkles-duo" /></template>
