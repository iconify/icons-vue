<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oky3v059h.css';
import '../../css/f/foe0t-bls.css';
import '../../css/s/ssgiq9b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oky3v059h"/><circle transform="rotate(-180 11 11)" class="foe0t-bls"/><path class="ssgiq9b_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:pen-bold" /></template>
