<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rs7apxeqd.css';
import '../../css/m/mguyo9biy.css';
import '../../css/o/oqagr1bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rs7apxeqd"/><path class="mguyo9biy"/><path class="oqagr1bdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:product-launch-laptop" /></template>
