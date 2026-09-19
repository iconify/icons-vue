<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/z9f0un12z.css';
import '../../css/t/tnbpgjkvm.css';
import '../../css/p/pyd8uurcz.css';
import '../../css/v/vdlq2ibar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="z9f0un12z"/><path class="tnbpgjkvm"/><circle class="pyd8uurcz"/><path class="vdlq2ibar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:satellite" /></template>
