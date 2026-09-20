<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/u8u0ujbfn.css';
import '../../css/t/tq86e6b7c.css';
import '../../css/u/u3nlt5bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u8u0ujbfn"/><path class="tq86e6b7c"/><path class="u3nlt5bzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wallet-off" /></template>
