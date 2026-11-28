<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8vpysbgw.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r8hlyibay.css';
import '../../css/y/yxdu62y1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8vpysbgw secondary"/><g class="dt0cm9dhy primary"><path class="r8hlyibay"/><path class="yxdu62y1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:thermometer-duo" /></template>
