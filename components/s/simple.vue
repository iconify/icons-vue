<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjdjckgkp.css';
import '../../css/s/sy3etbb8p.css';
import '../../css/p/ps55_-69a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle transform="rotate(-45 36 36)" class="gjdjckgkp"/><path class="sy3etbb8p"/><circle class="ps55_-69a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:simple" /></template>
