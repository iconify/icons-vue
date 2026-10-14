<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm7uaeb1c.css';
import '../../css/t/tc3e2jyph.css';
import '../../css/l/l0ij5ccyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="rm7uaeb1c"><path class="tc3e2jyph"/><path class="l0ij5ccyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:pin" /></template>
