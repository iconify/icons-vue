<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x9fb59bts.css';
import '../../css/h/hj5n3xbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="ft5dv1b6b"><rect class="x9fb59bts"/><path class="hj5n3xbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:orshot" /></template>
