<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcanjw_pl.css';
import '../../css/w/wx8v4gq2k.css';
import '../../css/z/zrbbkmbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wcanjw_pl"/><path class="wx8v4gq2k"/><path class="zrbbkmbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vector-pen-48" /></template>
