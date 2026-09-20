<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/z__w1mbdy.css';
import '../../css/u/upaxagjrx.css';
import '../../css/g/ga7t0girt.css';
import '../../css/c/chuhguiil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z__w1mbdy"/><path class="upaxagjrx"/><path class="ga7t0girt"/><path class="chuhguiil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:passport-broken" /></template>
