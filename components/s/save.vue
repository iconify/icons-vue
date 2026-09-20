<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq8rzkbds.css';
import '../../css/m/mmxhl-bkw.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/h/hlray_uja.css';
import '../../css/t/tzwk1-biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bq8rzkbds"/><circle class="mmxhl-bkw"/><g class="ij2x_72vy"><path class="hlray_uja"/><circle class="tzwk1-biw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:save" /></template>
