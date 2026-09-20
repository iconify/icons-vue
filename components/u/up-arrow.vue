<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp-6ebbmc.css';
import '../../css/l/ljs5lpfqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="gp-6ebbmc"/><path class="ljs5lpfqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:up-arrow" /></template>
