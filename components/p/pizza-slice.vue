<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m6pkdzb0p.css';
import '../../css/j/jbfeyeo7i.css';
import '../../css/x/x6-sqeb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m6pkdzb0p"/><path class="jbfeyeo7i"/><path class="x6-sqeb_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pizza-slice" /></template>
