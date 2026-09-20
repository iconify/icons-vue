<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrck--npu.css';
import '../../css/a/a3kaa3-qw.css';
import '../../css/f/fhtwuabpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="mrck--npu"><path class="a3kaa3-qw"/><path class="fhtwuabpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:mtmt" /></template>
