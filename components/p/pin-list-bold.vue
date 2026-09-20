<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h_nk4118m.css';
import '../../css/q/qrw1gubvo.css';
import '../../css/g/g79mtgboy.css';
import '../../css/g/g4z6abbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h_nk4118m"/><path clip-rule="evenodd" class="qrw1gubvo"/><path class="g79mtgboy"/><path clip-rule="evenodd" class="g4z6abbdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pin-list-bold" /></template>
