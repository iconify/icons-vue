<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/r/r29e52ykz.css';
import '../../css/k/kgx6i7brh.css';
import '../../css/m/mlnvvshov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="r29e52ykz"/><path class="kgx6i7brh"/><path class="mlnvvshov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:typescript-def" /></template>
