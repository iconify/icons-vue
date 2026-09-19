<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utnljdo3d.css';
import '../../css/p/pw5u487pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utnljdo3d"/><path class="pw5u487pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wallet-note-filled" /></template>
