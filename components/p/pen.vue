<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xpkp6q-rg.css';
import '../../css/f/foe0t-bls.css';
import '../../css/d/dllpr8t9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xpkp6q-rg"/><circle transform="rotate(-180 11 11)" class="foe0t-bls"/><path class="dllpr8t9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:pen" /></template>
