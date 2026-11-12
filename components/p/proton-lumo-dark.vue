<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6515jepd.css';
import '../../css/c/c97n50bhy.css';
import '../../css/z/z1zkdbgsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6515jepd"/><path class="c97n50bhy"/><path class="z1zkdbgsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-lumo-dark" /></template>
