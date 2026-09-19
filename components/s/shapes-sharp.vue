<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6gsu_bib.css';
import '../../css/h/hn50n_brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6gsu_bib"/><path class="hn50n_brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:shapes-sharp" /></template>
