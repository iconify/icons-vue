<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyhpkdsso.css';
import '../../css/x/xf-7ownph.css';
import '../../css/f/fhmm_kygi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyhpkdsso"/><path class="xf-7ownph"/><path class="fhmm_kygi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-horizontal-bold" /></template>
