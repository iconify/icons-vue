<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l113mebii.css';
import '../../css/k/klnbdfb1f.css';
import '../../css/z/zsoc3xbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l113mebii"/><path class="klnbdfb1f"/><path class="zsoc3xbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:table-rows-split-duotone" /></template>
