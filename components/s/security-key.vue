<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pbji87ens.css';
import '../../css/x/x20ovybwp.css';
import '../../css/u/ueob06b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pbji87ens"/><path class="x20ovybwp"/><path class="ueob06b-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:security-key" /></template>
