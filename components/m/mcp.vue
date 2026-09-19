<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leig0z_lw.css';
import '../../css/u/uitb-4b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leig0z_lw"/><path class="uitb-4b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:mcp" /></template>
