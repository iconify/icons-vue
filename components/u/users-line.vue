<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/n7a4osb1i.css';
import '../../css/h/h47p_644n.css';
import '../../css/q/q4f9vsb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="n7a4osb1i"/><path class="h47p_644n"/><path class="q4f9vsb6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:users-line" /></template>
