<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln0_z3bkf.css';
import '../../css/f/fg9x0cckk.css';
import '../../css/z/z8mmwq-ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ln0_z3bkf"/><path class="fg9x0cckk"/><path class="z8mmwq-ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-cable-48" /></template>
