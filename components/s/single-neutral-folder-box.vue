<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/fr1i81blz.css';
import '../../css/r/rxd12t4co.css';
import '../../css/r/rcha6sbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fr1i81blz"/><path class="rxd12t4co"/><path class="rcha6sbks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:single-neutral-folder-box" /></template>
