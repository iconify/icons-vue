<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tmxlmc_fk.css';
import '../../css/m/mo5jszbox.css';
import '../../css/p/p2gcfns7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tmxlmc_fk"/><path class="mo5jszbox"/><path class="p2gcfns7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scaling" /></template>
