<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uwx7j9nww.css';
import '../../css/l/llzh89b2x.css';
import '../../css/f/fk8bs2bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uwx7j9nww"/><path class="llzh89b2x"/><path class="fk8bs2bho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:soup-duotone" /></template>
