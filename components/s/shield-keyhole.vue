<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/krl7oozma.css';
import '../../css/h/hbks_38pg.css';
import '../../css/u/up-ygsbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="krl7oozma"/><circle class="hbks_38pg"/><path class="up-ygsbjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:shield-keyhole" /></template>
