<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r9d27nb_x.css';
import '../../css/k/k48mjsb2e.css';
import '../../css/v/v1yg_pbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r9d27nb_x"/><path class="k48mjsb2e"/><path class="v1yg_pbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tractor-duotone" /></template>
