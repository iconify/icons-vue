<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/g/gng9uo35b.css';
import '../../css/e/e648ybc7c.css';
import '../../css/c/ce7nwidet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="gng9uo35b"/><path clip-rule="evenodd" class="e648ybc7c"/><path class="ce7nwidet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:miner-outline" /></template>
