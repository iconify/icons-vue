<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i6b0xcc8y.css';
import '../../css/u/u7tmg3jvf.css';
import '../../css/k/kcrq3-bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6b0xcc8y"/><path class="u7tmg3jvf"/><path class="kcrq3-bds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:turtle-duotone" /></template>
