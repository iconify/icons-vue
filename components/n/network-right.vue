<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bwx6lbcne.css';
import '../../css/b/b0hlurj5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect transform="matrix(0 -1 -1 0 22 21)" class="bwx6lbcne"/><rect transform="matrix(0 -1 -1 0 7 15.5)" class="bwx6lbcne"/><rect transform="matrix(0 -1 -1 0 22 10)" class="bwx6lbcne"/><path class="b0hlurj5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:network-right" /></template>
