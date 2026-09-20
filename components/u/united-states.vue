<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uho2wkbps.css';
import '../../css/f/f4q1ngy9p.css';
import '../../css/i/igw_lbcrs.css';
import '../../css/l/l2hj_nb3x.css';
import '../../css/m/m2p93h8dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uho2wkbps"/><path class="f4q1ngy9p"/><path class="igw_lbcrs"/><path class="l2hj_nb3x"/><path class="m2p93h8dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:united-states" /></template>
