<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wjewqbtyv.css';
import '../../css/v/vh_i6z9mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect transform="matrix(1 0 0 -1 3 22)" class="wjewqbtyv"/><rect transform="matrix(1 0 0 -1 8.5 7)" class="wjewqbtyv"/><rect transform="matrix(1 0 0 -1 14 22)" class="wjewqbtyv"/><path class="vh_i6z9mv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:network-reverse-solid" /></template>
