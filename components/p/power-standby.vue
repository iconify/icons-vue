<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3cv_cc6k.css';
import '../../css/j/jaih09bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h3cv_cc6k"/><path class="jaih09bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:power-standby" /></template>
