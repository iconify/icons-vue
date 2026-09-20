<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fv5pcnpmp.css';
import '../../css/b/bnxnx5baf.css';
import '../../css/n/nli5obcdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fv5pcnpmp"/><path class="bnxnx5baf"/><path class="nli5obcdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:orbits" /></template>
