<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/v/vxck0rbst.css';
import '../../css/m/mqkui3bsu.css';
import '../../css/m/m-24ijb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="vxck0rbst"/><path class="mqkui3bsu"/><path class="m-24ijb3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:ruby-gem-lock" /></template>
