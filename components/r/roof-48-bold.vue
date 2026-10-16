<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2mlpnqnh.css';
import '../../css/d/d7knfxo3n.css';
import '../../css/k/kbe1bit3g.css';
import '../../css/p/pne_1mbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2mlpnqnh"/><path class="d7knfxo3n"/><path class="kbe1bit3g"/><path class="pne_1mbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:roof-48-bold" /></template>
