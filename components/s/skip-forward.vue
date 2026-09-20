<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/q/q771knb7e.css';
import '../../css/w/ws1d0fbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="icon-tabler nrj6p8qat"><path class="q771knb7e"/><path class="ws1d0fbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:skip-forward" /></template>
