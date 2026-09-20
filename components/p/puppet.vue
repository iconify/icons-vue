<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6yoqshmw.css';
import '../../css/z/z_e2vybpv.css';
import '../../css/g/g1_c90b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v6yoqshmw"/><path class="z_e2vybpv"/><path class="g1_c90b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:puppet" /></template>
