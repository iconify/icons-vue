<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/o/ojvzb-73z.css';
import '../../css/i/i_kaqkpye.css';
import '../../css/x/x5yfotb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="ojvzb-73z"/><path class="i_kaqkpye"/><path class="x5yfotb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:relay-outline" /></template>
