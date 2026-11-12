<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx6h-ubow.css';
import '../../css/s/sx13j5bfm.css';
import '../../css/i/itudopb2x.css';
import '../../css/u/ula6avb3k.css';
import '../../css/q/q_nf5abky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bx6h-ubow"/><path class="sx13j5bfm"/><path class="itudopb2x"/><path class="ula6avb3k"/><path class="q_nf5abky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:specifically-clementines" /></template>
