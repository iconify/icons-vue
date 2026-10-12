<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r3e-ge5gs.css';
import '../../css/u/uzmwkhbts.css';
import '../../css/p/p1cc6mb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r3e-ge5gs"/><path class="uzmwkhbts"/><path clip-rule="evenodd" class="p1cc6mb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tv-minimal-play-duotone" /></template>
