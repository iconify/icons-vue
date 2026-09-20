<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bopi9b9jn.css';
import '../../css/f/fxwnb7vgp.css';
import '../../css/n/nrw1tbcax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="bopi9b9jn"/><circle class="fxwnb7vgp"/><path class="nrw1tbcax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:spline" /></template>
