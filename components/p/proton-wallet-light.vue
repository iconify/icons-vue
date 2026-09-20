<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv5hqibas.css';
import '../../css/b/b1ivybqei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fv5hqibas"/><path class="b1ivybqei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-wallet-light" /></template>
