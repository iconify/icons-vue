<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k--qs-afs.css';
import '../../css/w/wtt-7nbfn.css';
import '../../css/f/fzdecdctz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k--qs-afs"/><path class="wtt-7nbfn"/><path class="fzdecdctz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rake-20-bold" /></template>
