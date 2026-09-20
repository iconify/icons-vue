<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_cyjh5hd.css';
import '../../css/r/r7zmfvpfr.css';
import '../../css/b/bh0se5bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n_cyjh5hd"><path class="r7zmfvpfr"/><path class="bh0se5bwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:toggle-off-line" /></template>
