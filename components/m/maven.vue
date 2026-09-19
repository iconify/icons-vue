<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/t/tk3tpbc4k.css';
import '../../css/d/dd4a45hkz.css';
import '../../css/k/k7x45obpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="tk3tpbc4k"/><path class="dd4a45hkz"/><path class="k7x45obpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:maven" /></template>
