<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r1b-rpbea.css';
import '../../css/w/w-_4s-3yn.css';
import '../../css/z/zesthlbac.css';
import '../../css/g/gn92_5b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r1b-rpbea"/><path class="w-_4s-3yn"/><path class="zesthlbac"/><path class="gn92_5b-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:shovel-rake-flat" /></template>
