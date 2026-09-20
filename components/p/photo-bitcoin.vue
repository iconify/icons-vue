<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/n_hes3sdi.css';
import '../../css/f/f2y748k3o.css';
import '../../css/n/nq-mj83lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_hes3sdi"/><path class="f2y748k3o"/><path class="nq-mj83lp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:photo-bitcoin" /></template>
