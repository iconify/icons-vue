<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z46p_cexp.css';
import '../../css/k/k0mqbqbfv.css';
import '../../css/j/j2mvxkhzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z46p_cexp"/><path class="k0mqbqbfv"/><path class="j2mvxkhzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spray-can-48-bold" /></template>
