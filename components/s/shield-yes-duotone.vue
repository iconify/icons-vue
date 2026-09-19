<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gk7xdgb3w.css';
import '../../css/a/anmzojybv.css';
import '../../css/w/wxjuyjb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gk7xdgb3w"/><path class="anmzojybv"/><path class="wxjuyjb5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:shield-yes-duotone" /></template>
