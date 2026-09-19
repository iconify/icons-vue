<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/f55vo7bfa.css';
import '../../css/h/h3jrti43j.css';
import '../../css/a/ahck4kpve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f55vo7bfa"/><path class="h3jrti43j"/><path class="ahck4kpve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:napkins-02" /></template>
