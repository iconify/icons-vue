<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nvz2em_xq.css';
import '../../css/g/gwvf-pb5g.css';
import '../../css/h/hzw4hpcrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nvz2em_xq"/><path class="gwvf-pb5g"/><path class="hzw4hpcrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:presentation-podium-notes" /></template>
