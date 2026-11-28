<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/az0b6nhta.css';
import '../../css/c/c8bgg3unk.css';
import '../../css/k/k--rt-b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="az0b6nhta"/><path class="c8bgg3unk"/><path class="k--rt-b3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-cog" /></template>
