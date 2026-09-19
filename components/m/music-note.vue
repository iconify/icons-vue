<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh_m54blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lh_m54blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:music-note" /></template>
