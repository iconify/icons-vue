<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isr_8i8ag.css';
import '../../css/t/tp3yspbee.css';
import '../../css/p/phox42bnd.css';
import '../../css/p/p23qiccjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="isr_8i8ag"/><path class="tp3yspbee"/><path class="phox42bnd"/><path class="p23qiccjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mic-off-48-bold" /></template>
