<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls6_xn_4i.css';
import '../../css/v/v8h4yw1tz.css';
import '../../css/f/fvkeyncuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ls6_xn_4i"><path class="v8h4yw1tz"/><path class="fvkeyncuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:next" /></template>
