<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v351mchmy.css';
import '../../css/y/yjcru9-ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v351mchmy"/><path class="yjcru9-ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monopile-48" /></template>
