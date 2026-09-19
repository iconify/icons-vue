<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm6odxb_u.css';
import '../../css/r/rivw31b0j.css';
import '../../css/u/u4hlkiabp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lm6odxb_u"/><path class="rivw31b0j"/><path class="u4hlkiabp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:night-landscape" /></template>
