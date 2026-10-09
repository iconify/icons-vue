<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0oa-qzdz.css';
import '../../css/v/vdi-4w12d.css';
import '../../css/v/v-w5pabfp.css';
import '../../css/v/vv_vc2byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="vdi-4w12d"/><path class="v-w5pabfp"/><path class="vv_vc2byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermostat-20-bold" /></template>
