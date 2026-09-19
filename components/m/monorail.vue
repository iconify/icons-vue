<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fyc9_fbub.css';
import '../../css/n/nxclh67wn.css';
import '../../css/w/w0wtj8boi.css';
import '../../css/m/mgyhsryxo.css';
import '../../css/p/pe592cbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fyc9_fbub"/><path class="nxclh67wn"/><path class="w0wtj8boi"/><path class="mgyhsryxo"/><path clip-rule="evenodd" class="pe592cbgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:monorail" /></template>
