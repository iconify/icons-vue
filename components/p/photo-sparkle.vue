<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u6z9jmr-h.css';
import '../../css/q/q5cqyabqx.css';
import '../../css/n/nqsi145hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u6z9jmr-h"/><circle class="q5cqyabqx"/><path class="nqsi145hz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:photo-sparkle" /></template>
