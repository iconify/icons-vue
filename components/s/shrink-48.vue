<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agcsd6j3i.css';
import '../../css/r/rps7bbcge.css';
import '../../css/n/nrn2j2qgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="agcsd6j3i"/><path class="rps7bbcge"/><path class="nrn2j2qgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shrink-48" /></template>
