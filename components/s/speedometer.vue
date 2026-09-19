<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o24e-tbjw.css';
import '../../css/j/jzcm3cc4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o24e-tbjw"/><path class="jzcm3cc4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:speedometer" /></template>
