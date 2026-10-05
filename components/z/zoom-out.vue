<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/a/abwis6bpt.css';
import '../../css/f/fop159nlm.css';
import '../../css/m/mofdx0msy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="abwis6bpt"/><path class="fop159nlm"/><path class="mofdx0msy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:zoom-out" /></template>
