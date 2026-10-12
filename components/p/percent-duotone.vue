<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/clnmdacqy.css';
import '../../css/w/wy_dkvg4c.css';
import '../../css/d/d_i7zccah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="clnmdacqy"/><path class="wy_dkvg4c"/><path class="d_i7zccah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:percent-duotone" /></template>
