<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-au2bijw.css';
import '../../css/j/jv20dbsyk.css';
import '../../css/i/ijutckbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-au2bijw"/><path class="jv20dbsyk"/><path class="ijutckbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-forms-light" /></template>
