<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a0it0b3fh.css';
import '../../css/d/dnmg3kr7o.css';
import '../../css/p/pulfy-giw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="a0it0b3fh"/><path class="dnmg3kr7o"/><path clip-rule="evenodd" class="pulfy-giw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medicines-outline-24px" /></template>
