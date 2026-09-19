<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unnb5obww.css';
import '../../css/w/wybknb96j.css';
import '../../css/f/ff6avabmc.css';
import '../../css/n/nnqfly97l.css';
import '../../css/x/xc81b0btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unnb5obww"/><path class="wybknb96j"/><path class="ff6avabmc"/><path class="nnqfly97l"/><path class="xc81b0btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:rocket" /></template>
