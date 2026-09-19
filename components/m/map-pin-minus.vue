<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uzrxt9cks.css';
import '../../css/v/vhig07y8s.css';
import '../../css/n/nbr52gbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="uzrxt9cks"/><path class="vhig07y8s"/><path class="nbr52gbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:map-pin-minus" /></template>
