<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/p2705r1-z.css';
import '../../css/g/g48w89bvm.css';
import '../../css/i/it2w4qb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2705r1-z"/><path class="g48w89bvm"/><path class="it2w4qb0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-send-01" /></template>
