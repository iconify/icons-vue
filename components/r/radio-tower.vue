<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f08q9dl9p.css';
import '../../css/k/kg5bfdcux.css';
import '../../css/s/s8od9eyyg.css';
import '../../css/d/dgzh063rl.css';
import '../../css/z/zdx9ddceq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="f08q9dl9p"/><circle class="f08q9dl9p"/><path class="kg5bfdcux"/><path class="s8od9eyyg"/><path class="dgzh063rl"/><path class="zdx9ddceq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:radio-tower" /></template>
