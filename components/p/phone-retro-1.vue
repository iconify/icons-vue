<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/to1w_vb_c.css';
import '../../css/n/nnax-acty.css';
import '../../css/p/p4fncyb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="to1w_vb_c"/><path class="nnax-acty"/><path class="p4fncyb8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:phone-retro-1" /></template>
