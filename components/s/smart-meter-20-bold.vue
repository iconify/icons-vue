<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4w28heyk.css';
import '../../css/n/nmtbxqbkt.css';
import '../../css/r/rz5zv0blr.css';
import '../../css/h/hbfxshwmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e4w28heyk"/><path class="nmtbxqbkt"/><path class="rz5zv0blr"/><path class="hbfxshwmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-meter-20-bold" /></template>
