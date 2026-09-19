<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uzrxt9cks.css';
import '../../css/n/nbr52gbso.css';
import '../../css/h/h-ecn2bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="uzrxt9cks"/><path class="nbr52gbso"/><path class="h-ecn2bgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:remove-pin-alt" /></template>
