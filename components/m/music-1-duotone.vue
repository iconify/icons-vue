<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tje8mb0vx.css';
import '../../css/u/u-6_p02jg.css';
import '../../css/n/n98jbmb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="tje8mb0vx"/><circle class="u-6_p02jg"/><path class="n98jbmb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:music-1-duotone" /></template>
