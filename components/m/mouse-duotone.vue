<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ytlbb5b4z.css';
import '../../css/h/hoo05jbdp.css';
import '../../css/q/qi136vumn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ytlbb5b4z"/><path class="hoo05jbdp"/><path class="qi136vumn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-duotone" /></template>
