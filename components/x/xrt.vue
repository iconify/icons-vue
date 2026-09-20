<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2r_kg_ej.css';
import '../../css/t/tkbvg7s4e.css';
import '../../css/d/d6f1x5bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a2r_kg_ej"/><path class="tkbvg7s4e"/><path class="d6f1x5bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xrt" /></template>
