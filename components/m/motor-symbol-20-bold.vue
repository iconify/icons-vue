<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx326_ber.css';
import '../../css/g/g1nn1ub5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mx326_ber"/><path class="g1nn1ub5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:motor-symbol-20-bold" /></template>
